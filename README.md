# edward-cloud
# edward-cloud
# edward-cloud
psql -U postgres


CREATE DATABASE nextcloud;
CREATE USER nextcloud WITH PASSWORD 'nextcloudpass';
GRANT ALL PRIVILEGES ON DATABASE nextcloud TO nextcloud;

CREATE DATABASE immich;
CREATE USER immich WITH PASSWORD 'immich';
GRANT ALL PRIVILEGES ON DATABASE immich TO immich;


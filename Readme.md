<h1 >Weferral API</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000" />
  <img src="https://img.shields.io/badge/node-%3E%3D11.8.0-blue.svg" />
</p>

## Description
  A RESTFUL API built for Weferral

### Author
Ezeokeke Uche 
* Email: <ezeokeke.remigius@gmail.com>

* Github: [@ezehuche](https://github.com/ezehuche)
* Twitter: [@Ezeokekeuche](https://twitter.com/Ezeokekeuche)

mkdir temp\
cd temp\
git clone https://github.com/timofverberg/weferral-api\
git clone https://github.com/timofverberg/weferral\
cd weferral-api\
docker-compose up -d\

Visit: http://localhost:8080\
System: PostgreSQL\
Server: database\
Username: postgres\
Password: example (set in compose.yaml)\

Create database -> Name: weferral -> Save

Visit: http://localhost:3500\
Database Host: database\
Database User: postgres\
Database Name: weferral (Same as previously named in adminer)\
Database Password: example (set in compose.yaml)\
Database Port: 5432\
SMTP Host: Set by your SMTP provider\
SMTP User: Set by your SMTP provider\
SMTP Password: Set by your SMTP provider\
SMTP Port: Set by your SMTP provider\
Email Address: Admin email, also used as sender for outgoing emails\
Password: Admin password\
Company Name: Should probably be set to something\
Company Address: Should probably be set to something\
Company Email: Should probably be set to something\
Company Phone Number: Should probably be set to something\
Cloudinary Name: Set by your cloudinary account\
Cloudinary Api Key: Set by your cloudinary account\
Cloudinary Api Secret: Set by your cloudinary account\



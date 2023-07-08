## Backend as a Service
### [Supabase](https://github.com/supabase/supabase) - ~52K stars
* Designed explicitly as an open source firebase alternative
* Typescript based
* Docker support

### [Appwrite](https://github.com/appwrite/appwrite) - ~32K stars
* Written in JavaScript and PHP
* Docker based
* Realtime support across all services
* Advanced security features (virus-scanning, data encryption, auto SSL, rate-limiting)
* Cross-platform: supports Web, Flutter, Desktop, Mobile and backend - over 10 SDKs: https://appwrite.io/docs/sdks
* Cloud Functions with +15 runtimes in multiple languages

### [PocketBase](https://github.com/pocketbase/pocketbase) - ~24k stars
* Go based, with Svelte frontend
* Doesn't seem to be an official dockerfile/image but there are unofficial images on [dockerhub](https://hub.docker.com/search?q=pocketbase)
* SQLite database
* Not used it but seems better for smaller projects

### [Parse Server](https://github.com/parse-community/parse-server) - ~20K stars
* JavaScript based
* MongoDB or PostgreSQL
* Has dockerfile

### [nakama](https://github.com/heroiclabs/nakama) - ~7.2K stars
* Go based
* Has official Docker images
* CockroachDB (or another Postgres wire-compatible server)
* Designed for use with games

### [nhost](https://github.com/nhost/nhost) - ~6.7K stars
* Written as a firebase alternative with GraphQL support
* Typescript based
* Includes docker-compose example
* See also [Hasura Backend Plus](https://github.com/nhost/hasura-backend-plus)

### [Kuzzle](https://github.com/kuzzleio/kuzzle) - ~1.3k stars
* JavaScript based
* Elasticsearch as a NoSQL document storage
* Has Docker Compose file

### [para](https://github.com/Erudika/para) - ~500 stars
* Java based
* Has official Docker images
* Database agnostic

### [LoopBack 4](https://github.com/strongloop/loopback-next) - ~4k stars
* More of an api development platform than a BaaS, added here because could be good starting point if developing own BaaS
* TypeScript and JavaScript based

### [Conduit](https://github.com/ConduitPlatform/Conduit) - ~300 stars
* TypeScript based
* Seems to still be in early development
* Database: MongoDB, PostgreSQL
* Database APIs: REST, GraphQL
* Storage: local, Azure Cloud, Google Cloud, Amazon S3 Cloud
* Auth: local, 2FA, Google, Facebook, Twitch, Slack, Figma, GitHub, GitLab, Microsoft, magic link
* Email: Mailgun, Sendgrid, Mandrill, SMTP
* Also has modules for: SMS, chat, forms, routing, push notifications

## Other services
These services aren't exactly Backend-as-a-Service as I understand it, but might still be useful. For now I'll just add links, and I'll add summaries later on.

### [SurrealDB](https://github.com/surrealdb/surrealdb) - ~21k stars
### [directus](https://github.com/directus/directus) - ~22k stars
### [strapi](https://github.com/strapi/strapi) - ~54k stars
### [Userbase](https://github.com/smallbets/userbase) - ~2.2k stars

## Discontinued BaaS
### [CloudBoost](https://github.com/CloudBoost/cloudboost) - ~1.4k stars
* Last commit in Nov 2020
* JavaScript based
* Has Docker Compose file
* MongoDB database

### [Apache Usergrid](https://github.com/apache/usergrid) - ~1k stars 
* Last commit in Dec 2020
* Java based 
* cassandra database

### [SkyGear](https://github.com/SkygearIO/skygear-server) - ~400 stars
* Last commit in Jun 2020
* Seems v. complete but not many users (harder to fix issues)
* Go based

## Further notes
* Platform as a service? Is one needed alongside BaaS? Dokku markets itself as mini heroku, maybe a good one to try first
(e.g. Flynn, tsuru, openshift, dokku, cloud foundry)

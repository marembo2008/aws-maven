### DigitalOcean Space Support
- Provides additional extension endpoint through `SpaceWagon`
- Uses the same aws sdk s3 client, with aws key and secrets

### Using the wagon
- apps must be run within the new deployments maven dockerfiles, which has integrated the wagon with maven library extensions
- this is necessary to be able to load the parent pom during build

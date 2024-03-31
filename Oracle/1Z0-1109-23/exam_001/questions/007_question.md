# As a Cloud Engineer, you are asked to manage the OCI Container Registry, which hosts Docker container images. You are directed to delete all the images within a tenancy region that have not been pulled for over 72 hours to avoid billing charges for the storage space they consume. Which action should you perform to handle this requirement?

> Since the requirement is to delete all images within a tenancy region that have not been pulled for over 72 hours, setting up a global image retention policy is the best option. This allows for a systematic and automated approach to deleting old, unused images, based on selection criteria.

1. [ ] For each old, unused image, select Delete Image from the Actions menu and confirm that you want to delete the image.
1. [ ] Set up local image retention policies to delete images automatically based on selection criteria
1. [ ] Periodically delete old, unused images using Docker CLI
1. [x] Set up a global image retention policy to delete images automatically based on selection criteria

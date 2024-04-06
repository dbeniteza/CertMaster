# Suppose you have created a Dockerfile for your application, and you want to convert it into a Docker image to be able to run it on a container. Which command should you use to achieve this?

> The "docker build" command is used to build an image from a Dockerfile. The "-t" option is used to specify the name and optionally a tag for the image. So, by running the command "docker build -t image_name:tag_name ." in the same directory as your Dockerfile, you can create a Docker image with the specified name and tag. The dot "." at the end of the command specifies the build context, which is the location of the files that are used to build the image.

1. [ ] docker convert -t image_name:tag_name
1. [ ] docker run -t image_name:tag_name
1. [ ] docker create -t image_name:tag_name
1. [x] docker build -t image_name:tag_name

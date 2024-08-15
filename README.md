# harness-iacm-images

custom images for harness iacm

## Dockerfile

simple retag of an image (let's us leverage the "build and push" step in harness ci)

## Dockerfile.harness_terraform

installing extra tools needed in terraform/tofu steps

## .harness/build_custom_images.yaml

harness pipeline to

1. get latest default image versions
2. build/copy iacm related images and push to registry
3. configure harness to use custom images by default in all iacm pipelines

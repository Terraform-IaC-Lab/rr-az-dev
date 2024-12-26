# Your Collie Kit

Build your own set of Collie [kit modules](https://landingzone.meshcloud.io/reference/kit-module.html) in this folder.

## Getting Started

```shell
collie kit new "aws/organization-policies"   # generate a new IaC module skeleton
collie kit apply "aws/organization-policies" # apply the module to a cloud platform in your foundation
collie foundation deploy "my-foundation"     # deploy the module to your cloud foundation
```

You can build your own kit modules from scratch or fork existing kit modules from the [Collie Hub](https://github.com/meshcloud/collie-hub/tree/main/kit)
by copying them here.

> Beware that kit modules identifiers must always have a cloud provider prefix like `aws/my-module` in their name.

## Documentation

This page is also included in your cloud foundation's documentation generated with `collie foundation docs`. Use this
document to describe anything that engineers working on the kit need to know.

![mu-cfn_nag](logo-small.png)

# Overview

Extension for [mu](https://github.com/stelligent/mu) to add [cfn_nag](https://github.com/stelligent/cfn_nag) to your continuous delivery pipeline.

To use, add the following to your `mu.yml`:

```
extensions:
- url: https://github.com/stelligent/mu-cfn_nag/archive/v0.1.zip
```

For more details about how to extensions in mu, check out the [wiki](https://github.com/stelligent/mu/wiki/Custom-CloudFormation#extensions) or the [blog post](https://stelligent.com/2018/03/23/validating-aws-cloudformation-templates-with-cfn_nag-and-mu/) introducing the extension.

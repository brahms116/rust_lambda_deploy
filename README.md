# Demo Rust Lambda Function

This is a demo rust lambda function with Api Gateway Proxy which utilises AWS CodeBuild, and AWS SAM to deploy. This is done using a custom AWS CodeBuild image, based off of the custom-al2-sam-build from AWS, extended with an installation of Rust. The CodeBuild project compiles the rust program and deploys it via SAM.

There is a future plan to revisit this and write much more clearer blog on this setup.

# 1. Intro

## Setup

1. Ensure you have completed the [Workshop setup directions](../README.md)

## Steps

1. Create an empty folder 

    ```
    $ mkdir ~/qconlondon/
    ```

1. Create a new Pulumi project

    ```
    $ pulumi new
    ```

    Pick the `aws-typescript` template, and use the `eu-west-1` region.  Say `yes` at the end to deploy the example.

1. Open the code in your editor/IDE

    ```
    $ code .
    ```

1. Check out the files generated by the template:

    * `index.ts` for your Pulumi program
    * `package.json` and `tsconfig.json` for Node and TypeScript configuration
    * `Pulumi.yaml` and `Pulumi.dev.yaml` for your Pulumi project and stack configuration

1. Visit the Pulumi console

    Open the link that was printed at the end of your first deployment in your browser.

    ```
    $ open https://app.pulumi.com/lukehoban/qconlondon/dev/updates/1
    ```

    Checkout the Activity and Resource tabs.  Click the link on your bucket to view it in the AWS Console.

1. The end result of these steps is availble in the [step1](./step`) folder.
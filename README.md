# Welcome to Kapetas Github

Here, you'll find an overview of the various repositories we have, their purpose, and their licensing.

## Documentation

To learn more about how to use Kapeta, please visit our knowledge base:
[https://docs.kapeta.com/](https://docs.kapeta.com/)

## Getting Help

We're always here to help - write us at support@kapeta.com

## Open Source

We want to engage as much as possible with the open-source community, and for that reason, we've open-sourced most of what we're doing.

Some of the more advanced and core parts of Kapeta are, however, licensed under the BUSL license - also known as source available. This is to protect our interests as a business and ensure that Kapeta will exist forever :)

All software installed on your machine or in your cloud will have its source available - with either an MIT or BUSL license.

## Repositories

### Desktop Application

License: BUSL-1.1

The desktop application is the main app you use to interact with Kapeta. It's fully source-available and licensed under the BUSL.

The repositories that contain the various components of the desktop app are:

- https://github.com/kapetacom/app-desktop-builder - Main electron app
- https://github.com/kapetacom/local-cluster-service - Background worker that does all the file reads and writes
- https://github.com/kapetacom/ui-web-plan-editor - The main Kapeta editor UI

### SDKs

We have SDKs for each programming language we support - all MIT-licensed.

You can find them here:

- [Java SDK](https://github.com/search?q=topic%3Ajava-spring-sdk+org%3Akapetacom&type=Repositories)
- [NodeJS SDK](https://github.com/search?q=topic%3Anodejs-sdk+org%3Akapetacom&type=Repositories)
- [Browser SDK](https://github.com/search?q=topic%3Abrowser-sdk+org%3Akapetacom&type=Repositories)

### Providers

At the core of Kapeta, we have a series of what we call "providers" that provide support for block types, language targets, resource types, deployment targets, and more.

You can view them [here](https://github.com/search?q=topic%3Aproviders+org%3Akapetacom&type=Repositories).

To learn more about these concepts, have a look at our knowledge base page here: https://docs.kapeta.com/docs/providers

Providers are MIT licensed except Deployment Targets, which are BUSL licensed.

### Samples

We publish samples for different systems in Kapeta - you can find the source by clicking [here](https://github.com/search?q=topic%3Asamples+org%3Akapetacom&type=Repositories).

Samples are MIT-licensed.

### Insights

Insights is a collection of software components we add to your system to provide you with insights like logs and metrics - you can find the source by clicking [here](https://github.com/search?q=topic%3Ainsights+org%3Akapetacom&type=Repositories).

Insights are MIT-licensed

### UI Library

Because we want to encourage the forking and implementation of plugins/providers for Kapeta, we're also providing the UI library we use for building the existing providers. This makes it easy to copy and adjust things to your needs.

You can find them [here](https://github.com/search?q=topic%3Aui-library+org%3Akapetacom&type=Repositories) - the main one being [ui-web-components](https://github.com/kapetacom/ui-web-components)

The UI library is MIT licensed - except for ui-web-plan-editor, which is BUSL licensed.

### Cloud Services

As part of the Kapeta system, we also have several cloud services and web frontends. These will remain closed-sourced for now - but we aim to publish several, if not all, of them in the future.

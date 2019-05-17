# Structurizr for TypeScript

This GitHub repository is a port of [Structurizr for .NET](https://github.com/structurizr/dotnet) to TypeScript, in order to help you visualise, document and explore the software architecture of a software system. In summary, it allows you to create a software architecture model based upon Simon Brown's [C4 model](https://structurizr.com/help/c4).

## How to use

- Set up a new project similar to this [sample](https://github.com/ChristianEder/structurizr-typescript/tree/master/sample)
  > npm init\
  > npm install -D @types/node\
  > npm install -D tsc\
  > npm install -D typescript\
  > npm install -S structurizr-typescript
- Start coding your architecture model similar to the [sample index.ts](https://github.com/ChristianEder/structurizr-typescript/blob/master/sample/index.ts)
  - For more detailed documentation on how to use Structurizr, please refer to [Structurizr for .NET](https://github.com/structurizr/dotnet) - the usage is pretty much the same
  - In the current version of this package, just a few of Structurizrs features are already implemented. See [Limitations](#Limitations) section below

## Limitations

The current version of this package only supports:
- People, System & Container entities
- Relationships between those entities 
- System Context & Container diagrams

This specifically excludes:
- Component & Class entities as well as the related diagrams
- Custom styles
- Encrypted workspaces
- Dynamic diagrams
- Deployment diagrams
- Enterprise context diagrams

Also, as of now the package is not (automatically) tested yet - use at own risk :-)
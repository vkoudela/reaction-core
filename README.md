#Reaction Core

Reaction Core provides a core set of methods and templates for creating, connecting, and managing user carts, sessions, products, checkout and orders for Reaction Commerce.

```
meteor add reactioncommerce:core
```

If this is a newly created Meteor project:

```
meteor remove insecure
meteor remove autopublish
meteor add nemo64:bootstrap
```

Create [client/themes/custom.reaction.json](https://github.com/reactioncommerce/reaction/blob/master/client/themes/custom.reaction.json) and [client/themes/custom.bootstrap.json](https://github.com/reactioncommerce/reaction/blob/master/client/themes/custom.bootstrap.json). These files configure the default LESS theme.

```
mkdir -p client/themes
curl -o client/themes/custom.bootstrap.json https://raw.githubusercontent.com/reactioncommerce/reaction/master/client/themes/custom.bootstrap.json
curl -o client/themes/custom.reaction.json https://raw.githubusercontent.com/reactioncommerce/reaction/master/client/themes/custom.reaction.json
```

## Developer Documentation

[Meteor Documentation](http://docs.meteor.com)

[Getting started guide](http://thoughts.reactioncommerce.com/how-to-get-involved-with-reaction-commerce/)

[Installation](https://github.com/ongoworks/reaction-core/blob/master/docs/installation.md)

[Guidelines](https://github.com/ongoworks/reaction-core/blob/master/docs/conventions.md)

[Methods](https://github.com/ongoworks/reaction-core/blob/master/docs/methods.md)

[Package Development](https://github.com/ongoworks/reaction-core/blob/master/docs/packages.md)

[Theme Development](https://github.com/ongoworks/reaction-core/blob/master/docs/themes.md)

[i18n Translations](https://github.com/ongoworks/reaction-core/blob/master/docs/i18n.md)

[Template Development](https://github.com/ongoworks/reaction-core/blob/master/docs/templates.md)

[Deploying](https://github.com/ongoworks/reaction-core/blob/master/docs/deploying.md)


## Roadmap
For a high level review our roadmap, take a look at the vision page [Reaction Vision](http://reactioncommerce.com/vision)

For grouping of development channels by feature see project milestones: https://github.com/reactioncommerce/reaction/milestones

And finally for the kanban-esque, hardcore real time progress view, take a look our [waffle board](https://waffle.io/reactioncommerce/reaction)


## Issues
For development tasks/issues please use the [Reaction project issues](https://github.com/ongoworks/reaction/issues?state=open). We're keeping this as the central issue tracking for all [reactioncommerce:*](https://github.com/reactioncommerce/) packages. You can also view issues on our [waffle board](https://waffle.io/reactioncommerce/reaction).


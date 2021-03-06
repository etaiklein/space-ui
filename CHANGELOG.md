Changelog
=========

### 4.3.1
Make setting the initial state of stores and mediators reactive. This has the
benefit that one can take advantage of `Mongo.Collection#findOne` and other reactivity
features when initializing the state.

### 4.3.0
Use the new `Space.Object.mixin` capabilities to introduce the `Space.ui.Stateful`
mixin that encapsulates the state setting functionality that the store had and make
it available on mediators too.

### 4.2.1
Introduce Space.ui.Module with same mapping automation features as the previously
added Space.ui.Application

### 4.2.0
Updates to latest space package dependencies, especially to `space:messaging`
which introduced a simpler controller api for handling messages.

### 4.1.1
Fixes bug with reactivity when setting store state via `set`. It is non-reactive now.

### 4.1.0
Adds `Space.ui.Application` class with simplified api for setting up stores,
mediators and controllers.

### 4.0.1
Use latest space:messaging release

### 4.0.0

Upgrades:
---------
- Upgrades to `space:base@1.3.0`

Breaking Changes:
----------------
Replace the flux dispatcher and actions with more solid event architecture
called `space:messaging`. This also introduces type-checked events. Please
have a look at the TodoMVC example to see how the new system works.

### 3.4.4
Upgrades to `space:base@1.2.6`

### 3.4.3
Adds tests for store `state` related methods and improves its API

### 3.4.2
Upgrades to `space:base@1.2.4`

### 3.4.0
Removes iron-router suppport and its dependency on it.

### 3.3.0
Improves the Mediator api for creating template helpers and event handlers.

### 3.2.0
Adds simplified api for creating and dispatching actions (see TodoMVC example).

### 3.1.0
Introduces auto-mapping of mediators and templates via annotations.

### 3.0.0
Cleans up the mediator API and removed old relicts that are not used anymore.

### 2.0.0
Update to the latest 1.0.3 verison of iron:router and fast-render packages.

### 1.0.0
Publish first version to Meteor package system.

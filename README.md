# Ember + Three JS

With this addon, you will be able to show your Ember models in 3D space.

There are three levels, each represented by a Component class:
* Three-scene: the main scene, renderer, camera and pan/zoom controls
* Three-layer: contains bodies of one type of model, defines look and feel of its models
* Three-body: links to one model, listens to changes and triggers actions

For now, https://github.com/pinx/visualplanner-frontend is my playground.

Once this is working, I plan to extract the ThreeJS part into ember-cli-threejs.


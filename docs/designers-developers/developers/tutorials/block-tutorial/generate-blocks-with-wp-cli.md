# Generate Blocks with WP-CLI

## WARNING

**Deprecated:** It is not no longer recommended to use WP-CLI or create-guten-block to generate block scaffolding.

During the interim period while the Gutenberg team was building a modern block scaffolding tool, a project called "create-guten-block" became popular, and you will note this in many tutorials on building blocks with Gutenberg. Due to the need to maintain the tool over time in a normalized way, we now recommend you use the officially supported tool "create-block" - though we want to express our gratitude to the authors of that tool for moving the Gutenberg Project forward! 

Almost all the concepts and syntax still applies, so you will find that transitioning from blocks built in "create-guten-block" can be adapted to your new setup.

The official script to generate a block is the new [@wordpress/create-block](/packages/create-block/README.md) package. This package follows the new block directory guidelines, and creates the proper block, environment, and standards set by the project. See the new [Create a Block tutorial](/docs/designers-developers/developers/tutorials/create-block/readme.md) for a complete walk-through.

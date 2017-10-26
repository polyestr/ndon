---
 suffix: ""
 assets: "assets"
---
<? `![${displayName} logo][${@alias(`${assets}/logo.svg`, 'asset')}]` ?>
<?!>

<? `# ${displayName} ${suffix}` ?>
<?!>

<? `${description}` ?>
<?!>

<!--? `${@include('./about/FEATURES.md')}` ?>
<?!-->

<!--? `${@include('./about/EXPERIMENTAL.md')}` ?>
<?!-->

<!--? `${@include('./guides/INSTALLATION.md')}` ?>
<?!-->

<!--? `${@include('./guides/USAGE.md')}` ?>
<?!-->

<!--? `${@include('./about/CONCEPTS.md')}` ?>
<?!-->

<!--? `${@include('./about/FAQ.md')}` ?>
<?!-->

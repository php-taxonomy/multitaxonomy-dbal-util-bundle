These templates are used more like a library than a part of a bundle.

```php
$c->loadFromExtension('twig', [
    'paths' => [
        // '%kernel.project_dir%/vendor/php-taxonomy/multitaxonomy-dbal-util-bundle/templates' => 'MultiTaxonomyDbalUtilBundle',
        '%kernel.project_dir%/vendor/php-taxonomy/multitaxonomy-dbal-util-bundle/Resources/views' => 'MultiTaxonomyDbalUtilBundle',
    ],
]);
```

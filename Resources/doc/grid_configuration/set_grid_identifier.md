Set the identifier of the grid
==============================

You can set the identifier of a grid to manage easily the grid with css and javascript for instance.

You have to define the identifier of a grid if you use two grids with the same source on the same page.

The grid will have the identifier grid_<grid_id> in html pages. And every request will use this variable to query the grid.

## Usage

```php
<?php
...
$grid->setSource($source);

$grid->setId($id);
...
```
## Method parameters

|parameter|Type|Default value|Description|
|:--:|:--|:--|:--|:--|
|id|string|_none_|Identifier of the grid|

## Exemple

```php
<?php
...
$grid->setSource($source);

$grid->setId('user');
...
```
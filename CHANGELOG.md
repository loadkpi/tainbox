# Changelog

## 0.2.4

* Fix bug where `:readonly` behaved as `:writeonly` and vice versa

## 0.2.5

* `suppress_tainbox_initializer!` is inherited correctly

## 0.2.6

* raise `ArgumentError` if trying to assign a non-hash to `#attributes`

## 0.2.7

* Attribute is always set to nil and marked as not provided when the hash assigned via
`#attributes=` or `#new` does not have that attribute and the attribute does not have a default

## 0.2.8

* Prepend internal variables with 'tainbox_' to avoid clashes with client code
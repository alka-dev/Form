# Changelog

## 1.1.2 (2018-06-15)

  * fix issue in textarea helper with `value` attribute (introduced in 1.1.1)

## 1.1.1 (2018-06-14)

  * add attribute whitelist (id, class, style) to `formField`, `formChoise` helper.
  * improve docs by adding example of smarty with form collection and `ncform_option`.
  * improve docs by adding example of smarty `ncform_field` with `type="id"`, `type="name"`, `type="value"`.

## 1.1.0 (2018-06-10)

  * breaking change of behavior in validators so that null values are valid (like in symfony).

## 1.0.2 (2018-02-07)

  * add attribute whitelist (id, class, style) to overwrite whitelisted attributes in `formStart` helper.

## 1.0.1 (2017-09-13)

  * add option `COLLECTION_TYPE_ANY`. Binds payload to any matching entity.
  * add php7.1 to travis ci

## 1.0.0 (2017-05-25)

  * Initial release
# Информация

[![Support](https://cdn-storage.github.io/images/badges/info.support.svg)](https://webmasters.community/)
[![Documentation](https://cdn-storage.github.io/images/badges/info.documentation.svg)](https://mediawiki.webmasters.wiki/)
[![Source](https://cdn-storage.github.io/images/badges/info.source.svg)](https://github.com/factory-06/mediawiki-ext-rating)
[![Changelog](https://cdn-storage.github.io/images/badges/info.changelog.svg)](CHANGELOG.md)
[![Code of Conduct](https://cdn-storage.github.io/images/badges/info.coc.svg)](https://metainfo.github.io/coc/)
[![Contributing](https://cdn-storage.github.io/images/badges/info.contributing.svg)](https://metainfo.github.io/contributing/)
[![Authors](https://cdn-storage.github.io/images/badges/info.authors.svg)](AUTHORS)
[![Issues](https://cdn-storage.github.io/images/badges/info.issues.svg)](https://github.com/factory-06/mediawiki-ext-rating/issues)
[![Packagist](https://cdn-storage.github.io/images/badges/info.packagist.svg)](https://packagist.org/packages/metastore/mediawiki-ext-rating)
[![License](https://cdn-storage.github.io/images/badges/license.gpl-3.0.svg)](LICENSE)
[![Liberapay](https://cdn-storage.github.io/images/badges/donate.liberapay.svg)](https://liberapay.com/metadata/donate)
[![Patreon](https://cdn-storage.github.io/images/badges/donate.patreon.svg)](https://patreon.com/metadata)
[![By METADATA](https://cdn-storage.github.io/images/badges/by.metadata.svg)](https://metadata.foundation/)

Интеграция рейтинга в статью.

## Синтаксис

```
{{#rating: title = [TITLE]
  |count = [NUMBER]
  |icon-plus = fas fa-[ICON]
  |icon-minus = fas fa-[ICON]
}}
```

## Установка

1. Загрузите папки и файлы в директорию `extensions/MW_EXT_Rating`.
2. В самый низ файла `LocalSettings.php` добавьте строку:

```
wfLoadExtension( 'MW_EXT_Rating' );
```

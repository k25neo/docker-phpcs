# docker-phpcs
PHP_CodeSniffer


docker run --rm --volume ~/PhpstormProjects/document/core/models:/project zhuravlev74/phpcs --standard=PSR12 --extensions=php --report=diff --ignore=vendor/*,console/migrations/*,docs/*,tests/*,views/* .

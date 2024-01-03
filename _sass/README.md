I added this folder structure to remove some warnings in the
vanilla Alembic theme. Namely, the warning was:
```
Deprecation Warning: Using / for division outside of calc()
is deprecated and will be removed in Dart Sass 2.0.0.
```

All the files here are replacing the corresponding ones in
the vanilla Alembic theme (version 4.1). I modified only
```
_sass/sassline-base/_mixins.scss
_sass/sassline-base/_typography.scss
```
while
```
_sass/alembic.scss
_sass/_sassline-base.scss
```
are unmodified.

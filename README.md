# Doctrine 2 CodeIgniter
Doctrine 2 repository with (sub)modules (from Doctrine repo) to use in CodeIgniter 3 (or other framework or version).

This repository is designed to Doctrine installation without using composer.
Folders are linked as submodules (from Doctrine git) in order to facilitate the updating of specific repositories, and without code replication in our project repository.

Using in: https://github.com/jeffdrumgod/hapia/tree/master/app/vendors


## Git submodule inside of a submodule (nested submodules)

In your project, add submodule:
```
git submodule add https://github.com/jeffdrumgod/Doctrine2CodeIgniter.git
```

And after, update inner submodules.
```
git submodule update --init --recursive
```



[![Analytics](https://ga-beacon.appspot.com/UA-4214899-25/jeffdrumgod/Doctrine2CodeIgniter)](https://github.com/jeffdrumgod/Doctrine2CodeIgniter)

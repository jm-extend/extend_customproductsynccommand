# Extend Custom Product Sync Command
This module is overriding the original product sync to allow a new flag : --force or -f
to force the synchronization of the entire catalog

## how to install :
copy contents in app/code/Extend

you would end up with 
app/code/ExtendCustomProductSyncCommand

then run 

```bin/magento setup:di:compile```

you should then be able to run :

```bin/magento extend:sync:products --force```

or

```bin/magento extend:sync:products -f```


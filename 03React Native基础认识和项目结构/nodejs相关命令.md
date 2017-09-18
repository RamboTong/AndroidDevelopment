# node.js相关命令

Usage: node [options] [ -e script | script.js ] [arguments]
       node debug script.js [arguments]


Options:    
  -v, --version         print Node.js version  
  -e, --eval script     evaluate script  
  -p, --print           evaluate script and print result  
  -c, --check           syntax check script without executing  
  -i, --interactive     always enter the REPL even if stdin  
                        does not appear to be a terminal  
  -r, --require         module to preload (option can be repeated)  
  --no-deprecation      silence deprecation warnings  
  --trace-deprecation   show stack traces on deprecations  
  --throw-deprecation   throw an exception anytime a deprecated function is used  
  --no-warnings         silence all process warnings  
  --trace-warnings      show stack traces on process warnings  
  --trace-sync-io       show stack trace when use of sync IO  
                        is detected after the first tick  
  --track-heap-objects  track heap object allocations for heap snapshots  
  --prof-process        process v8 profiler output generated  
                        using --prof  
  --zero-fill-buffers   automatically zero-fill all newly allocated  
                        Buffer and SlowBuffer instances  
  --v8-options          print v8 command line options  
  --v8-pool-size=num    set v8's thread pool size  
  --tls-cipher-list=val    use an alternative default TLS cipher list  
  --use-bundled-ca         use bundled CA store (default)  
  --use-openssl-ca         use OpenSSL's default CA store  
  --openssl-config=path load OpenSSL configuration file from the  
                        specified file (overrides OPENSSL_CONF)  
  --icu-data-dir=dir    set ICU data load path to dir  
                        (overrides NODE_ICU_DATA)  
  --preserve-symlinks   preserve symbolic links when resolving  
                        and caching modules. 

Documentation can be found at [https://nodejs.org/](https://nodejs.org/)



Usage: npm <command>

where <command> is one of:  
    access, adduser, bin, bugs, c, cache, completion, config,
    ddp, dedupe, deprecate, dist-tag, docs, edit, explore, get,
    help, help-search, i, init, install, install-test, it, link,
    list, ln, login, logout, ls, outdated, owner, pack, ping,
    prefix, prune, publish, rb, rebuild, repo, restart, root,
    run, run-script, s, se, search, set, shrinkwrap, star,
    stars, start, stop, t, tag, team, test, tst, un, uninstall,
    unpublish, unstar, up, update, v, version, view, whoami  

npm <cmd> -h     quick help on <cmd>  
npm -l           display full usage info  
npm help <term>  search for help on <term>  
npm help npm     involved overview  

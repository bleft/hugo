---
date: 2016-04-09T23:00:06+02:00
title: "hugo benchmark"
slug: hugo_benchmark
url: /commands/hugo_benchmark/
---
## hugo benchmark

Benchmark hugo by building a site a number of times.

### Synopsis


Hugo can build a site many times over and analyze the running process
creating a benchmark.

```
hugo benchmark
```

### Options

```
  -b, --baseURL string          hostname (and path) to the root, e.g. http://spf13.com/
  -D, --buildDrafts             include content marked as draft
  -F, --buildFuture             include content with publishdate in the future
      --cacheDir string         filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --canonifyURLs            if true, all relative URLs will be canonicalized using baseURL
      --cleanDestinationDir     Remove files from destination not found in static directories
      --config string           config file (default is path/config.yaml|json|toml)
  -c, --contentDir string       filesystem path to content directory
  -n, --count int               number of times to build the site (default 13)
      --cpuprofile string       path/filename for the CPU profile file
  -d, --destination string      filesystem path to write files to
      --disableRSS              Do not build RSS files
      --disableSitemap          Do not build Sitemap file
      --forceSyncStatic         Copy all files when static is changed.
      --ignoreCache             Ignores the cache directory for reading but still writes to it
  -l, --layoutDir string        filesystem path to layout directory
      --memprofile string       path/filename for the memory profile file
      --noTimes                 Don't sync modification time of files
      --pluralizeListTitles     Pluralize titles in lists using inflect (default true)
      --preserveTaxonomyNames   Preserve taxonomy names as written ("Gérard Depardieu" vs "gerard-depardieu")
      --renderToMemory          render to memory (only useful for benchmark testing)
  -s, --source string           filesystem path to read files relative from
      --stepAnalysis            display memory and timing of different steps of the program
  -t, --theme string            theme to use (located in /themes/THEMENAME/)
      --uglyURLs                if true, use /filename.html instead of /filename/
```

### Options inherited from parent commands

```
      --log              Enable Logging
      --logFile string   Log File path (if set, logging enabled automatically)
  -v, --verbose          verbose output
      --verboseLog       verbose logging
```

### SEE ALSO
* [hugo](/commands/hugo/)	 - hugo builds your site

###### Auto generated by spf13/cobra on 9-Apr-2016

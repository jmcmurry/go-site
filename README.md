[![Build Status](https://travis-ci.org/geneontology/go-site.svg)](https://travis-ci.org/geneontology/go-site)

A collection of metadata, files, and tools associated with the GO public
website and geneontology.org web presence.

As well, the tracker is used as a catch-all for anything not tied to another GO project.

Every directory should have its own description.

# metadata

  The location of all core GO-related metadata. Most notably
  db-xrefs.yaml and users.yaml.
  
# scripts

  Maintenance and support scripts.

# drupal7

  The files that we're using tp modify our Drupal 7 installation from
  stock. This may also serve as a base for when we push onto a
  service.

# cgi-bin

  This files an scripts that we want to preserve from the old GO site.
  Ideally, any critical functionality can be rewritten in a simpler
  and more reusable way than the original.

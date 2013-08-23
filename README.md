puppet_dir-modules
==================

Konwn Issues
------------

* apt: can't switch version, since it causes a conflict (consider removing packages stage) "Found 1 dependency cycle:
(Anchor[apt::source::dotdeb] => Apt::Source[dotdeb] => Class[Apt_dotdeb] => Stage[packages] => Stage[main] => Class[Apt::Update] => Exec[apt_update] => Class[Apt::Update] => Anchor[apt::source::dotdeb])"
* dns: always triggers a refresh TODO: create issue


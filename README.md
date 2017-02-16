# zjail

Even easier than ezjail, zjail lays bare the very fabric of FreeBSD jails.

This would be better as a blog post, but I lost the original script once
already, so let's store it for safe keeping.

1. It will destroy `zroot/jails` with impunity
2. You'll need to have the source txz sets already downloaded
3. It assumes it can overwrite your `/etc/pf.conf`, `/etc/jail.conf`, and
    abuse `/etc/unbound/conf.d/secure.conf` freely.
4. It works on my laptop using wifi. Adjust the network settings.

I really did this as a learning tool for others, but it's a good starting point.



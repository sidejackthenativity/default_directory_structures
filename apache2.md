```bash
├── apache2.conf
├── conf-available
│   ├── charset.conf
│   ├── javascript-common.conf
│   ├── localized-error-pages.conf
│   ├── other-vhosts-access-log.conf
│   ├── security.conf
│   └── serve-cgi-bin.conf
├── conf-enabled
│   ├── charset.conf -> ../conf-available/charset.conf
│   ├── javascript-common.conf -> ../conf-available/javascript-common.conf
│   ├── localized-error-pages.conf -> ../conf-available/localized-error-pages.conf
│   ├── other-vhosts-access-log.conf -> ../conf-available/other-vhosts-access-log.conf
│   ├── security.conf -> ../conf-available/security.conf
│   └── serve-cgi-bin.conf -> ../conf-available/serve-cgi-bin.conf
├── envvars
├── magic
├── mods-available
│   ├── access_compat.load
│   ├── actions.conf
│   ├── actions.load
│   ├── alias.conf
│   ├── alias.load
│   ├── allowmethods.load
│   ├── asis.load
│   ├── auth_basic.load
│   ├── auth_digest.load
│   ├── auth_form.load
│   ├── authn_anon.load
│   ├── authn_core.load
│   ├── authn_dbd.load
│   ├── authn_dbm.load
│   ├── authn_file.load
│   ├── authn_socache.load
│   ├── authnz_fcgi.load
│   ├── authnz_ldap.load
│   ├── authz_core.load
│   ├── authz_dbd.load
│   ├── authz_dbm.load
│   ├── authz_groupfile.load
│   ├── authz_host.load
│   ├── authz_owner.load
│   ├── authz_user.load
│   ├── autoindex.conf
│   ├── autoindex.load
│   ├── brotli.load
│   ├── buffer.load
│   ├── cache_disk.conf
│   ├── cache_disk.load
│   ├── cache.load
│   ├── cache_socache.load
│   ├── cern_meta.load
│   ├── cgid.conf
│   ├── cgid.load
│   ├── cgi.load
│   ├── charset_lite.load
│   ├── data.load
│   ├── dav_fs.conf
│   ├── dav_fs.load
│   ├── dav.load
│   ├── dav_lock.load
│   ├── dbd.load
│   ├── deflate.conf
│   ├── deflate.load
│   ├── dialup.load
│   ├── dir.conf
│   ├── dir.load
│   ├── dump_io.load
│   ├── echo.load
│   ├── env.load
│   ├── expires.load
│   ├── ext_filter.load
│   ├── file_cache.load
│   ├── filter.load
│   ├── headers.load
│   ├── heartbeat.load
│   ├── heartmonitor.load
│   ├── http2.conf
│   ├── http2.load
│   ├── ident.load
│   ├── imagemap.load
│   ├── include.load
│   ├── info.conf
│   ├── info.load
│   ├── lbmethod_bybusyness.load
│   ├── lbmethod_byrequests.load
│   ├── lbmethod_bytraffic.load
│   ├── lbmethod_heartbeat.load
│   ├── ldap.conf
│   ├── ldap.load
│   ├── log_debug.load
│   ├── log_forensic.load
│   ├── lua.load
│   ├── macro.load
│   ├── md.load
│   ├── mime.conf
│   ├── mime.load
│   ├── mime_magic.conf
│   ├── mime_magic.load
│   ├── mpm_event.conf
│   ├── mpm_event.load
│   ├── mpm_prefork.conf
│   ├── mpm_prefork.load
│   ├── mpm_worker.conf
│   ├── mpm_worker.load
│   ├── negotiation.conf
│   ├── negotiation.load
│   ├── php7.4.conf
│   ├── php7.4.load
│   ├── proxy_ajp.load
│   ├── proxy_balancer.conf
│   ├── proxy_balancer.load
│   ├── proxy.conf
│   ├── proxy_connect.load
│   ├── proxy_express.load
│   ├── proxy_fcgi.load
│   ├── proxy_fdpass.load
│   ├── proxy_ftp.conf
│   ├── proxy_ftp.load
│   ├── proxy_hcheck.load
│   ├── proxy_html.conf
│   ├── proxy_html.load
│   ├── proxy_http2.load
│   ├── proxy_http.load
│   ├── proxy.load
│   ├── proxy_scgi.load
│   ├── proxy_uwsgi.load
│   ├── proxy_wstunnel.load
│   ├── ratelimit.load
│   ├── reflector.load
│   ├── remoteip.load
│   ├── reqtimeout.conf
│   ├── reqtimeout.load
│   ├── request.load
│   ├── rewrite.load
│   ├── sed.load
│   ├── session_cookie.load
│   ├── session_crypto.load
│   ├── session_dbd.load
│   ├── session.load
│   ├── setenvif.conf
│   ├── setenvif.load
│   ├── slotmem_plain.load
│   ├── slotmem_shm.load
│   ├── socache_dbm.load
│   ├── socache_memcache.load
│   ├── socache_redis.load
│   ├── socache_shmcb.load
│   ├── speling.load
│   ├── ssl.conf
│   ├── ssl.load
│   ├── status.conf
│   ├── status.load
│   ├── substitute.load
│   ├── suexec.load
│   ├── unique_id.load
│   ├── userdir.conf
│   ├── userdir.load
│   ├── usertrack.load
│   ├── vhost_alias.load
│   └── xml2enc.load
├── mods-enabled
│   ├── access_compat.load -> ../mods-available/access_compat.load
│   ├── alias.conf -> ../mods-available/alias.conf
│   ├── alias.load -> ../mods-available/alias.load
│   ├── auth_basic.load -> ../mods-available/auth_basic.load
│   ├── authn_core.load -> ../mods-available/authn_core.load
│   ├── authn_file.load -> ../mods-available/authn_file.load
│   ├── authz_core.load -> ../mods-available/authz_core.load
│   ├── authz_host.load -> ../mods-available/authz_host.load
│   ├── authz_user.load -> ../mods-available/authz_user.load
│   ├── autoindex.conf -> ../mods-available/autoindex.conf
│   ├── autoindex.load -> ../mods-available/autoindex.load
│   ├── deflate.conf -> ../mods-available/deflate.conf
│   ├── deflate.load -> ../mods-available/deflate.load
│   ├── dir.conf -> ../mods-available/dir.conf
│   ├── dir.load -> ../mods-available/dir.load
│   ├── env.load -> ../mods-available/env.load
│   ├── filter.load -> ../mods-available/filter.load
│   ├── mime.conf -> ../mods-available/mime.conf
│   ├── mime.load -> ../mods-available/mime.load
│   ├── mpm_prefork.conf -> ../mods-available/mpm_prefork.conf
│   ├── mpm_prefork.load -> ../mods-available/mpm_prefork.load
│   ├── negotiation.conf -> ../mods-available/negotiation.conf
│   ├── negotiation.load -> ../mods-available/negotiation.load
│   ├── php7.4.conf -> ../mods-available/php7.4.conf
│   ├── php7.4.load -> ../mods-available/php7.4.load
│   ├── reqtimeout.conf -> ../mods-available/reqtimeout.conf
│   ├── reqtimeout.load -> ../mods-available/reqtimeout.load
│   ├── setenvif.conf -> ../mods-available/setenvif.conf
│   ├── setenvif.load -> ../mods-available/setenvif.load
│   ├── status.conf -> ../mods-available/status.conf
│   └── status.load -> ../mods-available/status.load
├── ports.conf
├── sites-available
│   ├── 000-default.conf
│   └── default-ssl.conf
└── sites-enabled
    └── 000-default.conf -> ../sites-available/000-default.conf
    ```
    

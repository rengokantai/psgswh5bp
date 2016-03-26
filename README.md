####psgswh5bp

#####1
```
mod_autoindex
mod_deflate
mod_expires
mod_filter
mod_headers
mod_include
mod_mime
mod_rewrite
mod_setenvif
```


#####2
######crossdomain.xml
```
<cross-domain-policy>
    <!-- Read this: https://www.adobe.com/devnet/articles/crossdomain_policy_file_spec.html -->

    <!-- Most restrictive policy: -->
    <site-control permitted-cross-domain-policies="none"/>

    <!-- Least restrictive policy: -->
    <!--
    <site-control permitted-cross-domain-policies="all"/>
    <allow-access-from domain="*" to-ports="*" secure="false"/>
    <allow-http-request-headers-from domain="*" headers="*" secure="false"/>
    -->
    <allow-http-request-headers-from domain="*.domain.com" />
</cross-domain-policy>
```

```bash
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose> cd ui
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm install
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: bootstrap@4.4.1
npm warn Found: jquery@undefined
npm warn node_modules/jquery
npm warn
npm warn Could not resolve dependency:
npm warn peer jquery@"1.9.1 - 3" from bootstrap@4.4.1
npm warn node_modules/bootstrap
npm warn   bootstrap@"^4.4.1" from the root project
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: bootstrap@4.4.1
npm warn Found: popper.js@undefined
npm warn node_modules/popper.js
npm warn
npm warn Could not resolve dependency:
npm warn peer popper.js@"^1.16.0" from bootstrap@4.4.1
npm warn node_modules/bootstrap
npm warn   bootstrap@"^4.4.1" from the root project
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: tsutils@3.17.1
npm warn Found: typescript@undefined
npm warn node_modules/typescript
npm warn
npm warn Could not resolve dependency:
npm warn peer typescript@">=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev -beta || >= 3.7.0-dev || >= 3.7.0-beta" from tsutils@3.17.1
npm warn node_modules/tsutils
npm warn   tsutils@"^3.17.1" from @typescript-eslint/eslint-plugin@2.24.0
npm warn   node_modules/@typescript-eslint/eslint-plugin
npm warn   1 more (@typescript-eslint/typescript-estree)
etaddrinfo ENOTFOUND proxy_host
npm error network This is a problem related to network connectivity.
npm error network In most cases you are behind a proxy or have bad network settings.                                                                            et
npm error network
npm error network If you are behind a proxy, please make sure that the          ng
al\npm-cache\_logs\2025-05-06T19_25_18_913Z-debug-0.log
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm run start
                                                                                al
> ui@0.1.0 start
> cross-env REACT_APP_SERVICE_HOST=http://localhost:8080 react-scripts start    
konnte nicht gefunden werden.
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm run start

> ui@0.1.0 start
> cross-env REACT_APP_SERVICE_HOST=http://localhost:8080 react-scripts start    
Der Befehl "cross-env" ist entweder falsch geschrieben oder
konnte nicht gefunden werden.
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm run start

> ui@0.1.0 start

konnte nicht gefunden werden.
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm start 
> ui@0.1.0 start
> cross-env REACT_APP_SERVICE_HOST=http://localhost:8080 react-scripts start    

Der Befehl "cross-env" ist entweder falsch geschrieben oder
konnte nicht gefunden werden.
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> node -v   
v22.15.0
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm -v    
10.9.2
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm install cross-env
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: bootstrap@4.4.1
npm warn Found: jquery@undefined
npm warn node_modules/jquery
npm warn
npm warn Could not resolve dependency:
npm warn peer jquery@"1.9.1 - 3" from bootstrap@4.4.1
npm warn node_modules/bootstrap
npm warn   bootstrap@"^4.4.1" from the root project
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: bootstrap@4.4.1
npm warn Found: popper.js@undefined
npm warn node_modules/popper.js
npm warn
npm warn Could not resolve dependency:
npm warn peer popper.js@"^1.16.0" from bootstrap@4.4.1
npm warn node_modules/bootstrap
npm warn   bootstrap@"^4.4.1" from the root project
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: tsutils@3.17.1
npm warn Found: typescript@undefined
npm warn node_modules/typescript
npm warn
npm warn Could not resolve dependency:
npm warn peer typescript@">=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta" from tsutils@3.17.1
npm warn node_modules/tsutils
npm warn   tsutils@"^3.17.1" from @typescript-eslint/eslint-plugin@2.24.0       
npm warn   node_modules/@typescript-eslint/eslint-plugin
npm warn   1 more (@typescript-eslint/typescript-estree)
npm error code ENOTFOUND
npm error syscall getaddrinfo
: getaddrinfo ENOTFOUND proxy_host
npm error network This is a problem related to network connectivity.
npm error network In most cases you are behind a proxy or have bad network settings.
npm error network
npm error network If you are behind a proxy, please make sure that the
npm error network 'proxy' config is set properly.  See: 'npm help config'       
al\npm-cache\_logs\2025-05-06T19_38_18_475Z-debug-0.log
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> npm run start

> ui@0.1.0 start
> cross-env REACT_APP_SERVICE_HOST=http://localhost:8080 react-scripts start    

Der Befehl "cross-env" ist entweder falsch geschrieben oder
konnte nicht gefunden werden.
PS C:\Users\OnlyM\Denis Cloud Projects\docker-desktop-hub-compose\ui> rm -rf node_modules package-lock.json
entspricht.
+    ~~~
    + CategoryInfo          : InvalidArgument: (:) [Remove-Item], ParameterBin  
   dingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsoft.PowerShell.Comm  
   ands.RemoveItemCommand
 


```

NPM Error is haunting me now. I am receiving an NPM Error 

ERROR [build 5/7] RUN npm ci  








denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose$ cd services
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker b
[+] Building 226.9s (12/12) FINISHED                                                                       
 => [internal] load build definition from Dockerfile                                                       
 => => transferring dockerfile: 288B                                                                       
 => [internal] load metadata for docker.io/library/node:lts                                                
 => [auth] library/node:pull token for registry-1.docker.io                                                
 => [internal] load .dockerignore                                                                          
 => => transferring context: 2B                                                                            
 => [1/6] FROM docker.io/library/node:lts@sha256:a1f1274dadd49738bcd4cf552af43354bb781a7e9e3bc984cfeedc55ab
 => => resolve docker.io/library/node:lts@sha256:a1f1274dadd49738bcd4cf552af43354bb781a7e9e3bc984cfeedc55ab
 => [internal] load build context                                                                          
 => => transferring context: 543.35kB                                                                      
 => CACHED [2/6] WORKDIR /code                                                                             
 => [3/6] COPY package.json /code/package.json                                                             
 => [4/6] COPY package-lock.json /code/package-lock.json                                                   
 => [5/6] RUN npm ci                                                                                       
 => [6/6] COPY . /code                                                                                     
 => exporting to image                                                                                     
 => => exporting layers                                                                                    
 => => naming to docker.io/library/projects-svc:latest                                     018108          
                                        0.1s                                               70d2            
 => => unpacking to docker.io/library/projects-svc:latest                                  221b53a7c7d63b3d
                                       20.3s                                               a1bb113a114     
                                                                                                           
 2 warnings found (use docker --debug to expand):                                                          
 - LegacyKeyValueFormat: "ENV key=value" should be used instead of legacy "ENV key value" format (line 9)
 - LegacyKeyValueFormat: "ENV key=value" should be used instead of legacy "ENV key value" format (line 9)ormat (line 4)                                                                             ormat (line 4)
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker build . --no-cache
[+] Building 328.1s (12/12) FINISHED                                        docker:default
 => [internal] load build definition from Dockerfile                                  0.5s
 => => transferring dockerfile: 288B                                                  0.3s 
 => [internal] load metadata for docker.io/library/node:lts                           3.0s
 => [auth] library/node:pull token for registry-1.docker.io                           0.0s
 => [internal] load .dockerignore                                                     0.1s
 => => transferring context: 2B                                                       0.1s 
 => [1/6] FROM docker.io/library/node:lts@sha256:a1f1274dadd49738bcd4cf552af43354bb7  0.4s
 => => resolve docker.io/library/node:lts@sha256:a1f1274dadd49738bcd4cf552af43354bb7  0.4s 
 => [internal] load build context                                                   247.4s 
 => => transferring context: 543.20kB                                               247.1s 
 => CACHED [2/6] WORKDIR /code                                                        0.0s
 => [3/6] COPY package.json /code/package.json                                        0.6s 
 => [4/6] COPY package-lock.json /code/package-lock.json                              0.3s 
 => [5/6] RUN npm ci                                                                 26.9s
 => [6/6] COPY . /code                                                               16.9s
 => exporting to image                                                               30.6s
 => => exporting layers                                                              12.8s
 => => exporting manifest sha256:dd60f739d5b75d368ac43eb308ad6e4fa6234094b5402e1bf90  0.1s
 => => exporting config sha256:3364f68e5dcb611f666f2ad73f7194be36d92a55b66b47d921b6e  0.1s
 => => exporting attestation manifest sha256:f09e97a2e2524091ffa5f4a39f7abb391f9b95a  0.2s
 => => exporting manifest list sha256:1c31851516a551c5e904b19fc48884589519b316426950  0.1s
 => => naming to moby-dangling@sha256:1c31851516a551c5e904b19fc48884589519b316426950  0.0s
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker p
-bash: syntax error near unexpected token `newline'
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker i
REPOSITORY     TAG       IMAGE ID       CREATED          SIZE
<none>         <none>    1c31851516a5   12 minutes ago   1.7GB
projects-svc   latest    46c8f1dc8cf4   26 minutes ago   1.7GB
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker r
Untagged: projects-svc:latest
Deleted: sha256:46c8f1dc8cf4da0b898cea306b3d03cf377abecb1335d0c96135aa1bb113a114
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker i
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
<none>       <none>    1c31851516a5   15 minutes ago   1.7GB
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker t
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker i
REPOSITORY     TAG       IMAGE ID       CREATED          SIZE
ea3f74bb1c0b53b807
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker rrvices$ docker stop projects-svc
Error response from daemon: No such container: projects-svc                                rvices$ docker s
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker stop 870bd253f6b5bd86587d50a01430f598f9401ba6211043ea3f74bb1c0b53b807       rvices$ docker s
870bd253f6b5bd86587d50a01430f598f9401ba6211043ea3f74bb1c0b53b807
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker start 870bd253f6b5bd86587d50a01430f598f9401ba6211043ea3f74bb1c0b53b807      rvices$ docker s
870bd253f6b5bd86587d50a01430f598f9401ba6211043ea3f74bb1c0b53b807
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/sedenis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ rvices$  docker tag projects-svc dennis4057/projects-svc1:latest
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker push dennis4057/projects-svc1:latest
<3>WSL (4016 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
The push refers to repository [docker.io/dennis4057/projects-svc1]
c187b51b626e: Waiting 
ca513cad200b: Waiting
63964a8518f5: Waiting
f0238947aa07: Waiting
f6d15b46736f: Waiting
cf05a52c0235: Waiting
9cb3b3ec7bbe: Waiting
14aef774eb9d: Waiting
01380cc03ca2: Waiting
72467b56867f: Waiting
cab5cd4cc9ae: Waiting
49d235c5ae59: Waiting
e2de622173df: Waiting
81e10ae7ef78: Waiting
push access denied, repository does not exist or may require authorization: server message: insufficient_scope: authorization failed
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker push dennis4057/projects-svc
Using default tag: latest
<3>WSL (4095 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
The push refers to repository [docker.io/dennis4057/projects-svc]
tag does not exist: dennis4057/projects-svc:latest
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker lpommes427+?" docker.io
WARNING! Using --password via the CLI is insecure. Use --password-stdin.
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker lstdin < ~/
-bash: /home/denis: No such file or directory
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker platest
<3>WSL (4424 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
The push refers to repository [docker.io/dennis4057/projects-svc1]
tag does not exist: dennis4057/projects-svc1:latest
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker p
Using default tag: latest
<3>WSL (4458 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
The push refers to repository [docker.io/dennis4057/projects-svc]
tag does not exist: dennis4057/projects-svc:latest
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker lemail=herikoug@gmail.com docker.io
unknown flag: --email
See 'docker login --help'.
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker l

Usage:  docker login [OPTIONS] [SERVER]

Log in to a registry.
If no server is specified, the default is defined by the daemon.

Options:
  -p, --password string   Password
      --password-stdin    Take the password from stdin
  -u, --username string   Username
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ RUN echoogin -u "dennis4057" --password-stdin
RUN: command not found
Error: Cannot perform an interactive login from a non TTY device
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker lpommes427+?” docker.io
WARNING! Using --password via the CLI is insecure. Use --password-stdin.
Error response from daemon: Get "https://registry-1.docker.io/v2/": unauthorized: incorrect username or pas
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker l
Password: 
Error response from daemon: Get "https://registry-1.docker.io/v2/": unauthorized: incorrect username or pas
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker l
Password: 
<3>WSL (5097 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
Error saving credentials: error storing credentials - err: exit status 1, out: ``
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ pass rempers
Command 'pass' not found, but can be installed with:
sudo apt install pass
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ sudo apt
[sudo] password for denis: 
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  cpp cpp-13 cpp-13-x86-64-linux-gnu cpp-x86-64-linux-gnu gcc-13-base libauthen-sasl-perl libclone-perl lib
  libencode-locale-perl libfile-basedir-perl libfile-desktopentry-perl libfile-listing-perl libfile-mimeinf
  libgles2 libhtml-form-perl libhtml-format-perl libhtml-parser-perl libhtml-tagset-perl libhtml-tree-perl 
  libhttp-daemon-perl libhttp-date-perl libhttp-message-perl libhttp-negotiate-perl libice6 libio-html-perl
  libio-stringy-perl libipc-system-simple-perl libisl23 liblwp-mediatypes-perl liblwp-protocol-https-perl l
  libnet-dbus-perl libnet-http-perl libnet-smtp-ssl-perl libnet-ssleay-perl libqrencode4 libsm6 libtie-ixha
  libtry-tiny-perl liburi-perl libwww-perl libwww-robotrules-perl libx11-protocol-perl libxaw7 libxcb-shape
  libxml-parser-perl libxml-twig-perl libxml-xpathengine-perl libxmu6 libxpm4 libxt6t64 libxv1 libxxf86dga1
  qrencode tree wl-clipboard x11-utils x11-xserver-utils xclip xdg-utils zutty
Suggested packages:
  cpp-doc gcc-13-locales cpp-13-doc libdigest-hmac-perl libgssapi-perl libio-compress-brotli-perl libcrypt-
  libsub-name-perl libbusiness-isbn-perl libregexp-ipv6-perl libauthen-ntlm-perl libunicode-map8-perl libun
  xml-twig-tools libxml-simple-perl python ruby debhelper mesa-utils nickle cairo-5c xorg-docs-core
Recommended packages:
  luit
The following NEW packages will be installed:
  cpp cpp-13 cpp-13-x86-64-linux-gnu cpp-x86-64-linux-gnu gcc-13-base libauthen-sasl-perl libclone-perl lib
  libencode-locale-perl libfile-basedir-perl libfile-desktopentry-perl libfile-listing-perl libfile-mimeinf
  libgles2 libhtml-form-perl libhtml-format-perl libhtml-parser-perl libhtml-tagset-perl libhtml-tree-perl 
  libhttp-daemon-perl libhttp-date-perl libhttp-message-perl libhttp-negotiate-perl libice6 libio-html-perl
  libio-stringy-perl libipc-system-simple-perl libisl23 liblwp-mediatypes-perl liblwp-protocol-https-perl l
  libnet-dbus-perl libnet-http-perl libnet-smtp-ssl-perl libnet-ssleay-perl libqrencode4 libsm6 libtie-ixha
  libtry-tiny-perl liburi-perl libwww-perl libwww-robotrules-perl libx11-protocol-perl libxaw7 libxcb-shape
  libxml-parser-perl libxml-twig-perl libxml-xpathengine-perl libxmu6 libxpm4 libxt6t64 libxv1 libxxf86dga1
  qrencode tree wl-clipboard x11-utils x11-xserver-utils xclip xdg-utils zutty
0 upgraded, 70 newly installed, 0 to remove and 45 not upgraded.
Need to get 15.4 MB of archives.
After this operation, 46.4 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 gcc-13-base amd64 13.3.0-6ubuntu2~24.04 [51
Get:2 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libisl23 amd64 0.26-3build1.1 [680 kB]
Get:3 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libmpc3 amd64 1.3.1-1build1.1 [54.6 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 cpp-13-x86-64-linux-gnu amd64 13.3.0-6ubunt
Get:5 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 cpp-13 amd64 13.3.0-6ubuntu2~24.04 [1038 B]
Get:6 http://archive.ubuntu.com/ubuntu noble/main amd64 cpp-x86-64-linux-gnu amd64 4:13.2.0-7ubuntu1 [5326 
Get:7 http://archive.ubuntu.com/ubuntu noble/main amd64 cpp amd64 4:13.2.0-7ubuntu1 [22.4 kB]
Get:8 http://archive.ubuntu.com/ubuntu noble/main amd64 libclone-perl amd64 0.46-1build3 [10.7 kB]
Get:9 http://archive.ubuntu.com/ubuntu noble/main amd64 libdata-dump-perl all 1.25-1 [25.9 kB]
Get:10 http://archive.ubuntu.com/ubuntu noble/main amd64 libencode-locale-perl all 1.05-3 [11.6 kB]
Get:11 http://archive.ubuntu.com/ubuntu noble/main amd64 libipc-system-simple-perl all 1.30-2 [22.3 kB]
Get:12 http://archive.ubuntu.com/ubuntu noble/main amd64 libfile-basedir-perl all 0.09-2 [14.4 kB]
Get:13 http://archive.ubuntu.com/ubuntu noble/main amd64 liburi-perl all 5.27-1 [88.0 kB]
Get:14 http://archive.ubuntu.com/ubuntu noble/main amd64 libfile-desktopentry-perl all 0.22-3 [16.8 kB]
Get:15 http://archive.ubuntu.com/ubuntu noble/main amd64 libtimedate-perl all 2.3300-2 [34.0 kB]
Get:16 http://archive.ubuntu.com/ubuntu noble/main amd64 libhttp-date-perl all 6.06-1 [10.2 kB]
Get:17 http://archive.ubuntu.com/ubuntu noble/main amd64 libfile-listing-perl all 6.16-1 [11.3 kB]
Get:18 http://archive.ubuntu.com/ubuntu noble/main amd64 libfile-mimeinfo-perl all 0.34-1 [42.1 kB]
Get:19 http://archive.ubuntu.com/ubuntu noble/main amd64 libfont-afm-perl all 1.20-4 [13.0 kB]
Get:20 http://archive.ubuntu.com/ubuntu noble/main amd64 libhtml-tagset-perl all 3.20-6 [11.3 kB]
Get:21 http://archive.ubuntu.com/ubuntu noble/main amd64 libhtml-parser-perl amd64 3.81-1build3 [85.8 kB]
Get:22 http://archive.ubuntu.com/ubuntu noble/main amd64 libio-html-perl all 1.004-3 [15.9 kB]
Get:23 http://archive.ubuntu.com/ubuntu noble/main amd64 liblwp-mediatypes-perl all 6.04-2 [20.1 kB]
Get:24 http://archive.ubuntu.com/ubuntu noble/main amd64 libhttp-message-perl all 6.45-1ubuntu1 [78.2 kB]
Get:25 http://archive.ubuntu.com/ubuntu noble/main amd64 libhtml-form-perl all 6.11-1 [32.1 kB]
Get:26 http://archive.ubuntu.com/ubuntu noble/main amd64 libhtml-tree-perl all 5.07-3 [200 kB]
Get:27 http://archive.ubuntu.com/ubuntu noble/main amd64 libhtml-format-perl all 2.16-2 [36.9 kB]
Get:28 http://archive.ubuntu.com/ubuntu noble/main amd64 libhttp-cookies-perl all 6.11-1 [18.2 kB]
Get:29 http://archive.ubuntu.com/ubuntu noble/main amd64 libhttp-daemon-perl all 6.16-1 [22.4 kB]
Get:30 http://archive.ubuntu.com/ubuntu noble/main amd64 libhttp-negotiate-perl all 6.01-2 [12.4 kB]
Get:31 http://archive.ubuntu.com/ubuntu noble/main amd64 libice6 amd64 2:1.0.10-1build3 [41.4 kB]
Get:32 http://archive.ubuntu.com/ubuntu noble/main amd64 perl-openssl-defaults amd64 7build3 [6626 B]
Get:33 http://archive.ubuntu.com/ubuntu noble/main amd64 libnet-ssleay-perl amd64 1.94-1build4 [316 kB]
Get:34 http://archive.ubuntu.com/ubuntu noble/main amd64 libio-socket-ssl-perl all 2.085-1 [195 kB]
Get:35 http://archive.ubuntu.com/ubuntu noble/main amd64 libio-stringy-perl all 2.111-3 [55.8 kB]
Get:36 http://archive.ubuntu.com/ubuntu noble/main amd64 libnet-http-perl all 6.23-1 [22.3 kB]
Get:37 http://archive.ubuntu.com/ubuntu noble/main amd64 libtry-tiny-perl all 0.31-2 [20.8 kB]
Get:38 http://archive.ubuntu.com/ubuntu noble/main amd64 libwww-robotrules-perl all 6.02-1 [12.6 kB]
Get:39 http://archive.ubuntu.com/ubuntu noble/main amd64 libwww-perl all 6.76-1 [138 kB]
Get:40 http://archive.ubuntu.com/ubuntu noble/main amd64 liblwp-protocol-https-perl all 6.13-1 [9006 B]
Get:41 http://archive.ubuntu.com/ubuntu noble/main amd64 libnet-smtp-ssl-perl all 1.04-2 [6218 B]
Get:42 http://archive.ubuntu.com/ubuntu noble/main amd64 libmailtools-perl all 2.21-2 [80.4 kB]
Get:43 http://archive.ubuntu.com/ubuntu noble/main amd64 libxml-parser-perl amd64 2.47-1build3 [204 kB]
Get:44 http://archive.ubuntu.com/ubuntu noble/main amd64 libxml-twig-perl all 1:3.52-2 [158 kB]
Get:45 http://archive.ubuntu.com/ubuntu noble/main amd64 libnet-dbus-perl amd64 1.2.0-2build3 [165 kB]
Get:46 http://archive.ubuntu.com/ubuntu noble/universe amd64 libqrencode4 amd64 4.1.1-1build2 [25.0 kB]
Get:47 http://archive.ubuntu.com/ubuntu noble/main amd64 libsm6 amd64 2:1.2.3-1build3 [15.7 kB]
Get:48 http://archive.ubuntu.com/ubuntu noble/main amd64 libtie-ixhash-perl all 1.23-4 [11.3 kB]
Get:49 http://archive.ubuntu.com/ubuntu noble/main amd64 libx11-protocol-perl all 0.56-9 [122 kB]
Get:50 http://archive.ubuntu.com/ubuntu noble/main amd64 libxt6t64 amd64 1:1.2.1-1.2build1 [171 kB]
Get:51 http://archive.ubuntu.com/ubuntu noble/main amd64 libxmu6 amd64 2:1.1.3-3build2 [47.6 kB]
Get:52 http://archive.ubuntu.com/ubuntu noble/main amd64 libxpm4 amd64 1:3.5.17-1build2 [36.5 kB]
Get:53 http://archive.ubuntu.com/ubuntu noble/main amd64 libxaw7 amd64 2:1.0.14-1build2 [187 kB]
Get:54 http://archive.ubuntu.com/ubuntu noble/main amd64 libxcb-shape0 amd64 1.15-1ubuntu2 [6100 B]
Get:55 http://archive.ubuntu.com/ubuntu noble/main amd64 libxft2 amd64 2.3.6-1build1 [45.3 kB]
Get:56 http://archive.ubuntu.com/ubuntu noble/main amd64 libxkbfile1 amd64 1:1.1.0-1build4 [70.0 kB]
Get:57 http://archive.ubuntu.com/ubuntu noble/main amd64 libxml-xpathengine-perl all 0.14-2 [32.6 kB]
Get:58 http://archive.ubuntu.com/ubuntu noble/main amd64 libxv1 amd64 2:1.0.11-1.1build1 [10.7 kB]
Get:59 http://archive.ubuntu.com/ubuntu noble/main amd64 libxxf86dga1 amd64 2:1.1.5-1build1 [11.6 kB]
Get:60 http://archive.ubuntu.com/ubuntu noble/universe amd64 tree amd64 2.1.1-2ubuntu3 [47.1 kB]
Get:61 http://archive.ubuntu.com/ubuntu noble/universe amd64 pass all 1.7.4-6 [34.5 kB]
Get:62 http://archive.ubuntu.com/ubuntu noble/universe amd64 qrencode amd64 4.1.1-1build2 [26.1 kB]
Get:63 http://archive.ubuntu.com/ubuntu noble/universe amd64 wl-clipboard amd64 2.2.1-1build1 [33.4 kB]
Get:64 http://archive.ubuntu.com/ubuntu noble/main amd64 x11-utils amd64 7.7+6build2 [189 kB]
Get:65 http://archive.ubuntu.com/ubuntu noble/main amd64 x11-xserver-utils amd64 7.7+10build2 [169 kB]
Setting up x11-xserver-utils (7.7+10build2) ...
Setting up liblwp-protocol-https-perl (6.13-1) ...
Setting up libwww-perl (6.76-1) ...
Setting up libxml-parser-perl (2.47-1build3) ...
Setting up libxml-twig-perl (1:3.52-2) ...
Setting up libnet-dbus-perl (1.2.0-2build3) ...
Processing triggers for man-db (2.12.0-4build2) ...
Processing triggers for hicolor-icon-theme (0.17-2) ...
Processing triggers for libc-bin (2.39-0ubuntu8.4) ...
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ pass rempers
Error: docker-credential-helpers is not in the password store.
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker l
Password: 
Error response from daemon: Get "https://registry-1.docker.io/v2/": unauthorized: incorrect username or pas
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker l
Password: 
Error response from daemon: Get "https://registry-1.docker.io/v2/": unauthorized: incorrect username or pas
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker l
Password: 
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker push dennis4057/projects-svc1:latest
<3>WSL (6251 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
rvices$ docker push dennis4057/projects-svc:latest
<3>WSL (6270 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
The push refers to repository [docker.io/dennis4057/projects-svc]                          rvices$ docker p
tag does not exist: dennis4057/projects-svc:latest
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker login -u "dennis4057"
Password:
Error response from daemon: Get "https://registry-1.docker.io/v2/": unauthorized: incorrect username or password
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker login -u dennis4057
Password:
Error response from daemon: Get "https://registry-1.docker.io/v2/": unauthorized: incorrect username or pasdenis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ 
Password: 
<3>WSL (6461 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
Error saving credentials: error storing credentials - err: exit status 1, out: ``
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker tag projects-svc dennis4057/projects-svc1:latest
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ docker push dennis4057/projects-svc1:latest
<3>WSL (6502 - ) ERROR: UtilAcceptVsock:251: accept4 failed 110
The push refers to repository [docker.io/dennis4057/projects-svc1]
01380cc03ca2: Waiting
63964a8518f5: Waiting
cab5cd4cc9ae: Waiting
e2de622173df: Waiting
81e10ae7ef78: Waiting
72467b56867f: Waiting
c187b51b626e: Waiting
49d235c5ae59: Waiting
f6d15b46736f: Waiting
cf05a52c0235: Waiting
f0238947aa07: Waiting
14aef774eb9d: Waiting
ca513cad200b: Waiting
9cb3b3ec7bbe: Waiting
push access denied, repository does not exist or may require authorization: failed to authorize: failed to fetch anonymous token: Get "https://auth.docker.io/token?scope=repository%3Adennis4057%2Fprojects-svc1%3Apull%2Cpush&service=registry.docker.io": push access denied, repository does not exist or may require authorization: server message: insufficient_scope: authorization failed
denis@DESKTOP-S89TDO7:/mnt/c/Users/OnlyM/Denis Cloud Projects/docker-desktop-hub-compose/services$ 


https://www.docker.com/blog/using-docker-desktop-and-docker-hub-together-part-1/
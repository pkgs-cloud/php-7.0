# PHP 7.0

RPM packages for RHEL / CentOS 7

### Installation

##### Install PHP 7.0

1. Install [**pkgs.cloud** release repository](https://github.com/pkgs-cloud/release)
2. `yum install php-7.0-release -y`
3. `yum install php -y`

##### List all available packages

```bash
yum --disablerepo="*" --enablerepo="pkgs.cloud-php-7.0" list available
```

### Current build

#### PHP 7.0.17 packages

```
php                          7.0.17
php-bcmath                   7.0.17
php-cli                      7.0.17
php-common                   7.0.17
php-dba                      7.0.17
php-dbg                      7.0.17
php-devel                    7.0.17
php-embedded                 7.0.17
php-enchant                  7.0.17
php-fpm                      7.0.17
php-gd                       7.0.17
php-gmp                      7.0.17
php-imap                     7.0.17
php-interbase                7.0.17
php-intl                     7.0.17
php-json                     7.0.17
php-ldap                     7.0.17
php-litespeed                7.0.17
php-mbstring                 7.0.17
php-mcrypt                   7.0.17
php-mysqlnd                  7.0.17
php-odbc                     7.0.17
php-opcache                  7.0.17
php-pdo                      7.0.17
php-pdo-dblib                7.0.17
php-pecl-apcu                5.1.8
php-pecl-apcu-bc             1.0.3
php-pecl-apcu-devel          5.1.8
php-pecl-geoip               1.1.1
php-pecl-igbinary            2.0.1
php-pecl-igbinary-devel      2.0.1
php-pecl-imagick             3.4.3
php-pecl-imagick-devel       3.4.3
php-pecl-lzf                 1.6.5
php-pecl-memcached           3.0.3
php-pecl-msgpack             2.0.2
php-pecl-msgpack-devel       2.0.2
php-pecl-redis               3.1.1
php-pecl-ssh2                1.0
php-pecl-xdebug              2.5.1
php-pgsql                    7.0.17
php-process                  7.0.17
php-pspell                   7.0.17
php-recode                   7.0.17
php-snappy                   0.1.6
php-snmp                     7.0.17
php-soap                     7.0.17
php-tidy                     7.0.17
php-xml                      7.0.17
php-xmlrpc                   7.0.17
```

#### Additional packages

```
apcu-panel                     5.1.8
gd                             2.2.4    
gd-devel                       2.2.4    
gd-progs                       2.2.4    
jemalloc                       3.6.0
jemalloc-devel                 3.6.0
memcached                      1.4.36   
memcached-devel                1.4.36   
openssl                        1.0.2k
openssl-libs                   1.0.2k
openssl-devel                  1.0.2k 
openssl-perl                   1.0.2k 
openssl-static                 1.0.2k 
redis                          3.2.8
```

### Help with RPM packages

- [Open an issue](https://github.com/pkgs-cloud/release/issues)

---

##### DISCLAIMER

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
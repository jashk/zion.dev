zion.local
===============


Entorno de desarrollo PHP 5.6 con apache 2.4


<h2>Run</h2>

<ul>
  <li>
    Intalar vagrant usando las instrucciones en 
    <a href="http://docs.vagrantup.com/v2/installation/" /target="_blank">Vagrant docs</a>
  </li>
  <li>Clonar este repositorio y ejcutar $ vagrant up</li>
  <li>Los directorios www representan /var/www/html</li>
  <li>Accesar a localhost:8080 (8181 para https)</li>
  <li>$ vagrant ssh</li>
</ul>

<h2>servername: zion.dev private_network: 192.168.56.101</h2>
```bash
#/etc/hosts
192.168.56.103 www.zion.dev
192.168.56.103 zion.dev
```

<h2>Módulos de apache</h2>

<ul>
  <li>proxy_fcgi</li>
  <li>rewrite</li>
  <li>ssl</li>
  <li>headers</li>
</ul>

<h2>Módulos de php</h2>

<ul>
  <li>cli</li>
  <li>intl</li>
  <li>gd</li>
  <li>imagick</li>
  <li>mbstring</li>
  <li>mcrypt</li>
  <li>mysql</li>
  <li>sqlite</li>
  <li>tidy</li>
  <li>xmlrpc</li>
  <li>curl</li>
  <li>common</li>
  <li>mysqlnd</li>
  <li>soap</li>
</ul>

<h2> xdebug : 9001</h2>
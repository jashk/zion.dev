basecentral.local
===============


Entorno de desarrollo PHP 5.5 con apache 2.4


<h2>Run</h2>

<ul>
  <li>
    Intalar vagrant usando las instrucciones en 
    <a href="http://docs.vagrantup.com/v2/installation/" /target="_blank">Vagrant docs</a>
  </li>
  <li>Clonar este repositorio y ejcutar $ vagrant up</li>
  <li>Los directorios conf y web representan /basecentral/apache/conf y /basecentral/apache/web/ respectivamente</li>
  <li>Accesar a localhost:8080 (8181 para https)</li>
  <li>$ vagrant ssh</li>
</ul>

<h2>servername: basecentral.dev private_network: 192.168.56.101</h2>
```bash
#/etc/hosts
192.168.56.101 www.basecentral.dev
192.168.56.101 basecentral.dev
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
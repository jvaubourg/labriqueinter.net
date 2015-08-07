---
title: La BriqueInter.net
home: yes
---

<section>
    <div id="video" class="video">
      <video width="800" height="450" src="video/labriqueinternet.webm" preload="metadata" controls="controls" tabindex="0">
        <track label="Français" kind="subtitles" srclang="fr" src="caption/fr.vtt">
        <button id="subtitles" type="button" data-state="subtitles">CC</button>
        Utilisez un navigateur récent pour visualiser cette vidéo.
      </video>
      <a href="#features" id="show-features-button">Liste des fonctionnalités (texte)</a>
    </div>

    <div id="features">
      La Brique Internet permet deux principaux usages :

      <ol>
        <li>
          <strong>Nettoyer son accès à Internet :</strong>
          <ul>
            <li><span>la Brique se branche simplement sur la box</span> de votre fournisseur d'accès à Internet (FAI)... c'est tout ;</li>
            <li><span>elle diffuse un second réseau WiFi</span>, que vous pouvez désormais utiliser pour accéder à Internet ;</li>
            <li>en passant par ce WiFi plutôt que celui de votre FAI, ce dernier <span>ne sera plus capable d'espionner, ni filtrer, ni brider votre accès</span> à Internet ;</li>
            <li>en bonus, <span>vos ordinateurs auront tous de l'IPv6 natif</span>, sans ne rien avoir eu à configurer ;</li>
            <li>si vous changez de FAI, <span>il suffit de débrancher et rebrancher la Brique</span> d'une box à l'autre, et il n'y a rien à reconfigurer ;</li>
            <li>vous disposez d'un Internet de confiance, sans filtrage et qui respecte la neutralité du Net, <span>peu importe sur quel accès Internet vous branchez votre Brique</span> (y compris sur un accès 3/4G).</li>
          </ul>
        </li>
        <li>
          <strong>S'auto-héberger :</strong>
          <ul>
            <li>grâce au logiciel <a href="http://yunohost.org">YunoHost</a>, <span>la Brique vous permet de conserver vos emails et autres données personnelles chez vous</span> plutôt que sur l'ordinateur d'un inconnu (ce qu'on appelle <em>le cloud</em>) ;</li>
            <li>YunoHost permet à quelqu'un qui s'intéresse à l'informatique, sans en être expert, d'<span>auto-héberger plein de services différents</span> (mail, partage de fichiers, blog, agenda en ligne, etc.) ;</li>
            <li>grâce à la Brique, qui est donc aussi un serveur, <span>vous n'avez pas à vous inquiéter des restrictions de votre FAI</span> : elles ont disparu ;</li>
            <li><span>votre serveur dispose d'un Internet neutre sans filtrage</span>, avec une IPv4 et des IPv6 fixes et il n'y a pas besoin de configurer la box de votre FAI ;</li>
            <li>si vous changez de FAI, <span>il suffit de débrancher et rebrancher la Brique d'une box à l'autre, et votre serveur est de nouveau disponible</span>, sans ne rien avoir eu à reconfigurer nul part ;</li>
            <li>si vous déménagez ou souhaitez couper l'électricité pour partir en vacances, <span>vous pouvez brancher votre Brique sur n'importe quel accès à Internet</span>, sans ne rien reconfigurer non plus ;</li>
            <li>vous pouvez aller <span>jusqu'à brancher votre serveur nomade sur un accès particulièrement restreint</span>, comme une connexion 3/4G et continuer de proposer vos services au monde entier.</li>
          </ul>
        </li>
        <li>
          <strong>Bonus :</strong>
          <ul>
            <li>avec une consommation de 2W maximum avec le WiFi actif, vous pouvez alimenter la Brique <span>avec une batterie ou un petit panneau solaire</span> (une batterie à 12€ permet de tenir 13h) ;</li>
            <li>le boîtier est <span><em>open-hardware</em> et les logiciels sont libres</span> ;</li>
            <li>la Brique peut également servir pour permettre d'<span>échanger des fichiers facilement et librement</span> lors d'un événement (ce qu'on appelle une <em>PirateBox</em>) ;</li>
            <li>vous pouvez également vous en servir <span>pour couvrir un événement public</span>, en déchargeant ainsi le propriétaire de la ligne Internet de sa responsabilité juridique.</li>
            <li>PS : vous pouvez utilisez une même Brique, <span>à la fois pour nettoyer votre accès à Internet grâce à son réseau WiFi, et héberger vos services</span> Internet.</li>
          </ul>
        </li>
      </ol>
    </div>

</section>

<section id="comment-ca-marche">
  <h2><span>Comment</span> ça marche ?</h2>

  <p>La Brique Internet, présentée dans la vidéo ci-dessus, est un simple boîtier VPN couplé à un serveur.</p>

  <p>Un VPN sert à relier <a href="https://fr.wikipedia.org/wiki/R%C3%A9seau_priv%C3%A9_virtuel">un ordinateur à un autre</a>, de façon sécurisée, de façon à ce qu'aucun intermédiaire sur Internet ne puisse lire le contenu des communications qui transitent. Pour que la Brique fonctionne, il faut lui configurer un accès VPN, qui lui permettra de créer un tunnel jusqu'à un autre ordinateur sur Internet. En vous connectant simplement en WiFi sur la Brique, vous pourrez aller sur Internet, en passant automatiquement au travers de ce tunnel chiffré. De cette façon, votre FAI ne peut plus ni vous espionner, ni vous brider ni vous filtrer. C'est le même mécanisme qui permet à la Brique d'être un serveur nomade.</p>

  <p>Schémas <a href="pdf/labriqueinternet_schemas.pdf">plus complets</a> que ceux présentés dans la vidéo :</p>

  <div class="pictures">
    <a href="pdf/labriqueinternet_schemas.pdf"><img src="/img/labriqueinternet_schemas_thumb.png" alt="Schémas" /></a>
  </div>

  <p>L'ordinateur auquel vous vous reliez par le VPN doit être géré par des gens de confiance. C'est pour cette raison qu'il est souhaitable de choisir une association, pour laquelle vous avez déjà rencontré les adhérents. Certaines associations vous fourniront directement le boîtier clé en main, avec votre accès VPN préconfiguré.</p>
</section>

<section id="comprendre-les-enjeux">
  <h2><span>Comment mieux comprendre</span> les enjeux ?</h2>

  <p>Ces trois conférences devraient vous aider à comprendre les enjeux liés à la vie privée, à l'auto-hébergement et à l'IPv6 :</p>

  <ul>
    <li><a href="http://ldn-fai.net/je-nai-rien-a-cacher/">Je n'ai rien à cacher</a></li>
    <li><a href="http://ldn-fai.net/liberer-internet-sexe-alcool-et-vie-privee/">Sexe, alcool et vie privée</a></li>
    <li><a href="http://ldn-fai.net/intranet-ipv4-ou-internet-ipv6/">Intranet IPv4 ou Internet IPv6</a></li>
  </ul>
</section>

<section id="avancement-du-projet">
  <h2><span>Quel est l'avancement</span> du projet ?</h2>

  <p>De nombreuses personnes utilisent déjà la Brique au quotidien, en tant que principal accès à Internet, pour héberger des services web, ou les deux à la fois.</p>

  <p style="text-align: center"><strong>Qu'attendez-vous pour ajouter votre Brique à l'Internet libre, neutre et décentralisé ?</strong></p>

  <div class="pictures" id="photos" class="nature">
    <a href="photos/labriqueinternet-nature.png"><img src="/img/labriqueinternet-nature_thumb.png" alt="Brique Internet" title="La Brique Internet" /></a>
    <a href="photos/labriqueinternet-solaire.png"><img src="/img/labriqueinternet-solaire_thumb.png" alt="Brique Internet (panneau solaire)" title="La Brique Internet, avec panneau solaire" /></a>
    <a href="photos/labriqueinternet-batterie.png"><img src="/img/labriqueinternet-batterie_thumb.png" alt="Brique Internet (batterie)" title="La Brique Internet, avec batterie" /></a>
  </div>

  <p>Pour se tenir au courant de l'avancement du projet, pour poser des questions ou pour émettre des suggestions, plusieurs canaux sont disponibles :</p>

  <ul>
    <li>Liste de discussion : <a href='https://listes.labriqueinter.net/mailman/listinfo/discussions'>discussions@listes.labriqueinter.net</a></li>
    <li>IRC : <a href='http://en.irc2go.com/webchat/?net=GeekNode&amp;room=labriqueinter.net'>#labriqueinter.net</a> sur irc.geeknode.org</li>
    <li>Twitter : <a href="https://twitter.com/une_brique">@Une_brique</a></li>
    <li>GitHub : <a href="https://github.com/labriqueinternet">labriqueinternet</a></li>
  </ul>
</section>

<section id="obtenir-une-brique">
  <h2><span>Comment obtenir</span> une Brique Internet ?</h2>

  <p>Les commandes groupées de matériel se font auprès d'associations locales (environ 60€ par Brique, grâce à une sympathique réduction sur le matériel, proposée par Olimex aux associations participantes).</p>

  <p>Les associations proposent en général de vous fournir la Brique complète, entièrement montée, installée et configurée avec un accès VPN : <strong>il ne vous restera plus qu'à la déballer et la brancher chez vous pour bénéficier de votre nouvel accès à Internet propre, sans rien avoir à faire d'autre</strong> (et installer ensuite des services web auto-hébergés si le cœur vous en dit, en quelques clics sur l'interface d'administration).</p>

  <p>Vous pouvez contacter une association <a href="http://db.ffdn.org">près de chez vous</a>, pour savoir si elle fournit des Briques Internet :</p>

  <div class="pictures">
    <a href="http://db.ffdn.org"><img src="/img/assos.png" alt="Associations de FFDN" /></a>
  </div>

  <p>Sinon, vous pouvez construire votre propre Brique vous-même, grâce aux liens de la section suivante.</p>
</section>

<section id="construire-une-brique">
  <h2><span>Comment construire</span> ma propre Brique ?</h2>

  <p>Les associations citées dans la section précédente vous permettront en général de directement recevoir une Brique clé en main. Pour ceux qui ne souhaitent pas passer par une association et qui souhaitent tout faire eux-même, la procédure reste très accessible, et les liens fournis dans cette section vous permettront d'y arriver facilement.</p>

  <p>Logiciels :</p>

  <ul>
    <li><a hreflang="en" href="http://build.labriqueinter.net">Image Debian/YunoHost pour A20-OLinuXino-LIME</a> (créée par nos soins, recompilable, et <a href="http://repo.labriqueinter.net">téléchargeable</a> en torrent ou HTTP)</li>
    <li><a href="https://yunohost.org/#/index_fr">Projet YunoHost</a> (<a href="http://build.yunohost.org">autres images Debian</a>)</li>
    <li><a hreflang="en" href="https://github.com/labriqueinternet/hotspot_ynh">Application WiFi Hotspot pour YunoHost</a></li>
    <li><a hreflang="en" href="https://github.com/labriqueinternet/vpnclient_ynh">Application VPN Client pour YunoHost</a></li>
    <li><a hreflang="en" href="https://github.com/labriqueinternet/piratebox_ynh">Application PirateBox pour YunoHost</a> (nécessite WiFi Hotspot)</li>
  </ul>

  <div class="pictures" id="photos">
    <a href="https://raw.githubusercontent.com/labriqueinternet/hotspot_ynh/master/screenshot.png"><img src="/img/screenshot-hotspot_thumb.png" alt="WiFi Hotspot" title="Interface web de WiFi Hotspot" /></a>
    <a href="https://github.com/jvaubourg/php-piratebox#screenshots"><img src="/img/screenshot-piratebox_thumb.png" alt="PirateBox" title="PirateBox" /></a>
    <a href="https://raw.githubusercontent.com/labriqueinternet/vpnclient_ynh/master/screenshot.png"><img src="/img/screenshot-vpnclient_thumb.png" alt="VPN Client" title="Interface web de VPN Client" /></a>
  </div>

  <p>Matériel proposé :</p>

  <ul>
    <li>Carte Olimex (<em>open-hardware</em>) : <a hreflang="en" href="https://www.olimex.com/Products/OLinuXino/A20/A20-OLinuXino-LIME/open-source-hardware">A20-OLinuXino-LIME</a></li>
    <li>Boîtier pour la carte : <a hreflang="en" href="https://www.olimex.com/Products/OLinuXino/A10/A10-OLinuXino-LIME-BOX/">A10-OLinuXino-LIME-BOX</a></li>
    <li>Adaptateur secteur (<a href="https://www.olimex.com/wiki/PWRJACK">port</a> 5V DC) pour la carte (un simple câble mini-USB suffit pour alimenter la carte, mais l'adaptateur est utile pour brancher un disque dur auto-alimenté dessus) : <a href="https://www.olimex.com/Products/Power/SY0605E-CHINA/">SY0605E-CHINA</a></li>
    <li>Antenne WiFi (pas <em>open-hardware</em>)
      <ul>
        <li>Version <a hreflang="en" href="http://www.fsf.org/news/ryf-certification-thinkpenguin-usb-with-atheros-chip">libre</a> (limitée à 7 connexions simultanées, <em>multissid</em> jusqu'à 2 AP) : <a href="http://fr.aliexpress.com/item/Atheros-AR9271-Chip-150Mbps-Mini-USB-Wifi-Adapter-with-5dBi-Antenna/32344771975.html">AR9271</a> (<a href="http://www.ebay.fr/itm/Mini-USB-Wifi-Adapter-150Mbps-Atheros-AR9271-Chip-with-5dBi-wifi-Antenna-C1846-/111719135679?pt=LH_DefaultDomain_0&amp;hash=item1a02fab9bf">autre lien</a>)</li>
        <li>Version <a hreflang="en" href="https://packages.debian.org/jessie/firmware-ralink">non-libre</a> (<em>multissid</em> jusqu'à 8 AP) : <a href="https://www.olimex.com/Products/USB-Modules/MOD-WIFI-R5370-ANT/">MOD-WIFI-R5370-ANT</a></li>
      </ul>
    <li>Carte micro-SD qui sert de disque dur interne : <a href="http://www.amazon.fr/Transcend-microSDHC-adaptateur-TS32GUSDU1E-Emballage/dp/B00CES44EO">Transcend Premium 300x Classe 10</a> (16 Go est suffisant)</li>
    <li>Batterie (13h d'autonomie, optionnelle) : <a hreflang="en" href="https://www.olimex.com/Products/Power/BATTERY-LIPO6600mAh/">BATTERY-LIPO6600mAh</a></li>
    <li>Panneau solaire (optionnel) : <a href="http://snootlab.com/lang-fr/seeedstudio/699-lipo-rider-pro-fr.html">LiPo Rider Pro</a>, <a href="http://snootlab.com/lang-fr/seeedstudio/702-panneau-solaire-3w-138x160-fr.html">PS 3W 138x160</a>, + 1 batterie (<a href="https://hackspark.fr/fr/catalogsearch/result/?q=lipo">autre vendeur</a>) - <a href="photos/labriqueinternet-solaire-details.png">Photo</a></li>
  </ul>

  <div class="pictures" id="photos">
    <a href="/img/boot1.png"><img src="/img/boot1_thumb.png" alt="Boot 1" /></a>
    <!-- <a href="/img/hardware.png"><img src="/img/hardware_thumb.png" alt="Hardware" /></a> -->
    <a href="/img/boot2.png"><img src="/img/boot2_thumb.png" alt="Boot 2" /></a>
  </div>

  <p>Prix du matériel détaillé ci-dessus pour 1 Brique complète (sans la batterie et le panneau solaire, mais avec les frais de port) :</p>

  <ul>
    <li>Environ 60€, dans le cadre d'une commande groupée associative (FFDN)</li>
    <li>Environ 70€, dans le cadre d'une commande groupée personnelle (à partir de 10 Briques)</li>
    <li>Environ 80€ sinon</li>
  </ul>

  <p>Décoration de la Brique et diffusion du projet :</p>

  <ul>
    <li>Un <a href="stuff/labriqueinternet-sticker.png">magnifique sticker</a> (<a href="stuff/labriqueinternet-sticker.svg">SVG</a>) à coller sur un boîtier Olimex (8cm x 5.5cm)</li>
    <li>Une <a href="stuff/labriqueinternet-poster-a3.png">superbe affiche</a> (<a href="stuff/labriqueinternet-poster-a3.svg">SVG</a>) à coller sur tous les murs (format A3)</li>
  </ul>
</section>

<section id="remplacer-vpn-par-tor">
  <h2><span>Remplacer le VPN</span> par Tor ?</h2>

  <div class="text">
    <p>Une extension de la Brique est <a href="https://github.com/labriqueinternet/torclient_ynh">désormais disponible</a> (nécessite WiFi Hotspot), pour fournir en plus un accès à Internet clé en main via <a href="https://www.torproject.org">Tor</a>.</p>

    <p>L'objectif est d'utiliser la clé WiFi pour diffuser deux réseaux WiFi : un pour un accès transparent par VPN et l'autre pour un accès transparent via Tor (et même un troisième pour une PirateBox). Cette extension se présente comme une simple application YunoHost supplémentaire, à installer.</p>

    <div class="pictures">
      <a href="/img/tor.png"><img src="/img/tor_thumb.png" alt="Tor" /></a>
    </div>

    <p>Toutes les requêtes Internet des périphériques connectés au WiFi sont anonymisées en passant par le réseau Tor. Toutefois, pour garantir un véritable anonymat (dissidents politiques, journalistes, etc.) et empêcher votre navigateur de divulguer des informations sur votre identité, il restera toujours préférable d'utiliser directement le <a href="https://www.torproject.org/download/download-easy.html">Tor Bundle</a> (uniquement pour le web et sur un ordinateur classique). De plus, conformément aux contraintes imposées par Tor, l'accès à Internet n'est pas neutre (limité à TCP et aux requêtes DNS en UDP).</p>
  </div>
</section>

<section id="anonymat-et-legislation">
  <h2><span>Anonymat</span> et législation ?</h2>

  <p>Concernant l'aspect « accès à Internet par VPN » : les associations de la fédération FDN ne garantissent en général pas l'anonymat vis-à-vis des autorités compétentes, ni aucune sorte d'impunité vis-à-vis de la loi française.</p>

  <p>La garantie qu'elles apportent est de ne coopérer avec la justice que dans le cadre strict des lois en vigueur. Par conséquent, aucune donnée ne sera fournie à quiconque, si la procédure légale associée n'est pas strictement suivie. Nous savons que ça n'est pas forcément le cas des fournisseurs d'accès grand public, qu'on peut légitimement soupçonner de fournir des informations sur simples appels téléphoniques émanant de policiers ou d'installer des accès privilégiées à leurs données, en dehors de toutes procédures légales (qui sont désormais amenées à être <a href="http://sous-surveillance.fr">plus ou moins facultatives</a>).</p>

  <p>Les tunnels VPN ne peuvent apporter une sorte d'anonymat vis-à-vis des autorités françaises, que si le fournisseur du service se trouve sous la juridiction d'un état réputé pour ne pas collaborer facilement avec la France (par exemple la Russie, et il faudra alors avoir confiance dans le fournisseur du service, et en la législation de ce pays).</p>

  <p>Mais, quel que soit le pays, configurer la Brique avec un fournisseur de VPN étranger (judicieusement choisi) sera particulièrement intéressant dans le cas d'un dissident politique ou d'un journaliste, qui souhaiterait se protéger des dérives sécuritaires de son pays, pour revendiquer plus de libertés.</p>
</section>

---
title: InternetCu.be
home: yes
---

<section>
    <div id="video" class="video">
      <video width="800" height="450" src="video/labriqueinternet.webm" preload="metadata" controls="controls" tabindex="0">
        <track label="English" kind="subtitles" srclang="en" src="caption/en.vtt" default>
        <button id="subtitles" type="button" data-state="subtitles">CC</button>
        Use a modern browser to watch this video.
      </video>
      <a href="#features" id="show-features-button">Features list (text)</a>
    </div>

    <div id="features">
      The Internet cube has two main uses:

      <ol>
        <li>
          <strong>Clean your internet access:</strong>
          <ul>
            <li><span>You simply connect the Cube to your Internet Service Provider (ISP) box</span>... and that's it ;</li>
            <li><span>It will start a second Wifi network</span>, which you can use to access the internet;</li>
            <li>By using this Wifi rather than the one from you ISP, <span>won't be able to spy, filter or restrict</span> your Internet connection;</li>
            <li>Furthermore, <span>your computers will automatically gain a native IPv6 access</span>, without the need to configure anything;</li>
            <li>If you decide to switch of ISP, <span>you can just unplug and replug the Cube from one box to the Other</span> and you won't need to reconfigure anything;</li>
            <li>You now have a Trusted Internet access, without filtering and respectful of the Net Neutrality, <span>regardless of where your connect your box</span>, it even works using 3G/4G.</li>
          </ul>
        </li>
        <li>
          <strong>Self Hosting:</strong>
          <ul>
            <li>thanks to the software <a href="http://yunohost.org">YunoHost</a>, <span>the Internet Cube allows you to store your emails and other personal data at your own place</span> instead of storing them on the computer of someone else (what is commonly referred today as <em>the cloud</em>);</li>
            <li>YunoHost allows anyone who is interested in IT, without being an expert, <span>to self-host a wide range of services</span> (emails, file sharing, blog, online calendar, etc...);</li>
            <li>thanks to the Cube, which is also an Internet server, <span>you don't have to worry about the restrictions of your ISP</span>: they have disappeared;</li>
            <li><span>you server is connected to an Internet access that respect Net Neutrality and which isn't censored</span>, with static IPv4 and IPv6 and there is no need to configure your ISP box;</li>
            <li>if you switch of ISP, <span>you only need to unplugged and replug the Internet Cube from the old box to the new one and your server will be available again</span> without the need of any configuration;</li>
            <li>if you move or switch off your electricity to go on vacation, <span>you can plug your Cube on any Internet access</span> without having to do any configuration;</li>
            <li><span>you can even connect your portable server to an especially restricted access,</span>, like a 3/4G connection and continue to offer your services to the whole world.</li>
          </ul>
        </li>
        <li>
          <strong>Bonus:</strong>
          <ul>
            <li>with a maximum consumption of only 2W with the Wifi activated, the Cube can be powered <span>via a battery or a small solar Panel</span> (a 12€ battery cell can last 13h);</li>
            <li>the box is in <span>open-hardware and all the software included are freesoftware</span>;</li>
            <li>the Internet Cube can also allows you to <span>share files easily</span> during an event (this is what we call a <em>PirateBox</em>) ;</li>
            <li>you can also use it <span>to provide Internet access at a public event</span>, when using someone else connection to free it's owner from liabilities.</li>
            <li>PS: you can use the same Cube <span>to clean your Internet access with its Wifi hotspot and host your Internet services</span>.</li>
          </ul>
        </li>
      </ol>
    </div>

</section>

<section id="how-does-it-works">
  <h2><span>How</span> does it works?</h2>

  <p>The Internet Cube, as presented in the video below, is a simple VPN box paired with a server.</p>

  <p>A VPN is used to <a href="https://en.wikipedia.org/wiki/Virtual_private_network">connect one computer to another</a>, in a secured way, a way that no intermediary on the internet can read the content of the communication that transit over it. For the Cube to work, it needs to be configured to access a VPN, that will allow to create a tunnel up to another computer on the internet. By connecting yourself to the Cube Wifi, you can surf the internet, through its encrypted tunnel. This way your Provider can't spy, limit or filter your connection. The same mechanism allows the Cube to act as a portable server.</p>

  <p>More complete <a hreflang="fr-FR" href="pdf/labriqueinternet_schemas.pdf">schematics</a> that the ones in the video:</p>

  <div class="pictures">
    <a href="pdf/labriqueinternet_schemas.pdf"><img src="/img/labriqueinternet_schemas_thumb.png" alt="Schémas" /></a>
  </div>

  <p>Of course, since your internet traffic will transit via this VPN, the distant computer to which you will connect it must be managed by people you trust. For that reason, it's better to choose an association whose members you have already met. Some of theses associations can provide you the Cube pre-configured to connect to them.</p>
</section>

<section id="understanding-the-stakes">
  <h2><span>How to have a better understanding</span> of the stakes?</h2>

  <p>These three conferences (in French) should help you understand the issues of privacy, self-hosting and IPv6:</p>

  <ul>
    <li><a hreflang="fr-FR" href="http://ldn-fai.net/je-nai-rien-a-cacher/">Je n'ai rien à cacher (I have nothing to hide)</a></li>
    <li><a hreflang="fr-FR" href="http://ldn-fai.net/liberer-internet-sexe-alcool-et-vie-privee/">Sexe, alcool et vie privée (Sex, alcohol and privacy)</a></li>
    <li><a hreflang="fr-FR" href="http://ldn-fai.net/intranet-ipv4-ou-internet-ipv6/">Intranet IPv4 ou Internet IPv6 (IPv4 intranet or IPv6 Internet)</a></li>
  </ul>
</section>

<section id="state-of-the-project">
  <h2><span>What is the state</span> of the project?</h2>

  <p>Many people already use the Cube every day, as main internet access, for hosting web services, or both at once.</p>

  <p style="text-align: center"><strong>What are you waiting for adding your own Cube to the free, neutral and decentralized internet?</strong></p>

  <div class="pictures" id="photos" class="nature">
    <a href="photos/labriqueinternet-nature.png"><img src="/img/labriqueinternet-nature_thumb.png" alt="Internet Cube" title="Internet Cube" /></a>
    <a href="photos/labriqueinternet-solaire.png"><img src="/img/labriqueinternet-solaire_thumb.png" alt="Internet Cube (solar panel)" title="Internet Cube, with solar panel" /></a>
    <a href="photos/labriqueinternet-batterie.png"><img src="/img/labriqueinternet-batterie_thumb.png" alt="Internet Cube (battery)" title="Internet Cube, with battery" /></a>
  </div>

  <p>To stay informed about the progress of the project, ask questions or make suggestions, several mediums are available:</p>

  <ul>
    <li>Mailing list: <a hreflang="fr-FR" href='https://listes.labriqueinter.net/mailman/listinfo/discussions'>discussions@listes.labriqueinter.net</a></li>
    <li>IRC: <a href='http://en.irc2go.com/webchat/?net=GeekNode&amp;room=labriqueinter.net'>#labriqueinter.net</a> sur irc.geeknode.org</li>
    <li>Twitter: <a href="https://twitter.com/une_brique">@Une_brique</a></li>
    <li>GitHub: <a href="https://github.com/labriqueinternet">labriqueinternet</a></li>
  </ul>
</section>

<section id="get-an-internet-cube">
  <h2><span>How to get</span> an Internet Cube?</h2>

  <p>Bulk orders are made by local associations (approximately 60€ per Cube, thanks to a nice price cut on the hardware, proposed by Olimex to the involved associations).</p>

  <p>Generally, the associations offer to provide you a plug-n-play Cube, fully assembled, installed and configured with a VPN access: <strong>you will only have to unpack it, and plug in it at home to take advantage of your new clean internet access, without anything else to do</strong> (and then install self-hosting web services, if you feel like it, in a few clicks thanks to the administration interface).</p>

  <p>You can contact an association <a href="http://db.ffdn.org">close to you</a>, to ask if they provide Internet Cubes:</p>

  <div class="pictures">
    <a href="http://db.ffdn.org"><img src="/img/assos.png" alt="Associations from the FFDN" /></a>
  </div>

  <p>Otherwise, you can build your own Cube all by yourself by following this information in the next section.</p>
</section>

<section id="build-an-internet-cube">
  <h2><span>How to build</span> my own Internet Cube?</h2>

  <p>The cited associations in the previous section will generally enable you to directly receive a plug-n-play Cube. For those who do no want to ask an association and want to do everything themselves, the process is simple, and the links provided in this section will allow you to do this easily.</p>

  <p>Software:</p>

  <ul>
    <li><a href="http://build.labriqueinter.net">Debian/YunoHost image for A20-OlinuXino-LIME</a> (made by us, recompilable and <a href="http://repo.labriqueinter.net">downloadable</a> by torrent or HTTP)</li>
    <li><a href="https://yunohost.org/#/index_en">YunoHost project</a> (<a href="http://build.yunohost.org">other Debian images</a>)</li>
    <li><a href="https://github.com/labriqueinternet/hotspot_ynh">Wifi Hotspot application for YunoHost</a></li>
    <li><a href="https://github.com/labriqueinternet/vpnclient_ynh">VPN Client application for YunoHost</a></li>
    <li><a href="https://github.com/labriqueinternet/piratebox_ynh">PirateBox application for YunoHost</a> (requires Wifi Hotspot)</li>
  </ul>

  <div class="pictures" id="photos">
    <a href="https://raw.githubusercontent.com/labriqueinternet/hotspot_ynh/master/screenshot.png"><img src="/img/screenshot-hotspot_thumb.png" alt="WiFi Hotspot" title="Web interface of WiFi Hotspot" /></a>
    <a href="https://github.com/jvaubourg/php-piratebox#screenshots"><img src="/img/screenshot-piratebox_thumb.png" alt="PirateBox" title="PirateBox" /></a>
    <a href="https://raw.githubusercontent.com/labriqueinternet/vpnclient_ynh/master/screenshot.png"><img src="/img/screenshot-vpnclient_thumb.png" alt="VPN Client" title="Web interface of VPN Client" /></a>
  </div>

  <p>Suggested hardware:</p>

  <ul>
    <li>Olimex board (open-hardware): <a href="https://www.olimex.com/Products/OLinuXino/A20/A20-OLinuXino-LIME/open-source-hardware">A20-OLinuXino-LIME</a></li>
    <li>Case for the board: <a href="https://www.olimex.com/Products/OLinuXino/A10/A10-OLinuXino-LIME-BOX/">A10-OLinuXino-LIME-BOX</a></li>
    <li>Sector adaptor (<a href="https://www.olimex.com/wiki/PWRJACK">power jack</a> 5V DC) for the board (a simple mini-USB cable is enough to powered to board, but the adapter is useful to plug a self-powered hard drive): <a href="https://www.olimex.com/Products/Power/SY0605E-CHINA/">SY0605E-CHINA</a></li>
    <li>Wifi antenna (not open-hardware)
      <ul>
        <li><a href="http://www.fsf.org/news/ryf-certification-thinkpenguin-usb-with-atheros-chip">Free Software</a> version (limited to 7 simultaneous connections, <em>multissid</em> up to 2 AP): <a href="http://fr.aliexpress.com/item/Atheros-AR9271-Chip-150Mbps-Mini-USB-Wifi-Adapter-with-5dBi-Antenna/32344771975.html">AR9271</a> (<a href="http://www.ebay.fr/itm/Mini-USB-Wifi-Adapter-150Mbps-Atheros-AR9271-Chip-with-5dBi-wifi-Antenna-C1846-/111719135679?pt=LH_DefaultDomain_0&amp;hash=item1a02fab9bf">another link</a>)</li>
        <li><a href="https://packages.debian.org/jessie/firmware-ralink">Non Free Software</a> version (<em>multissid</em> up to 8 AP) : <a href="https://www.olimex.com/Products/USB-Modules/MOD-WIFI-R5370-ANT/">MOD-WIFI-R5370-ANT</a></li>
      </ul>
    <li>Micro-SD card that is used as the internal hard drive: <a hreflang="fr-FR" href="http://www.amazon.fr/Transcend-microSDHC-adaptateur-TS32GUSDU1E-Emballage/dp/B00CES44EO">Transcend Premium 300x Class 10</a> (16 Go is enough)</li>
    <li>Battery (13h of autonomy, optional): <a href="https://www.olimex.com/Products/Power/BATTERY-LIPO6600mAh/">BATTERY-LIPO6600mAh</a></li>
    <li>Solar panel (optional): <a href="http://snootlab.com/lang-en/seeedstudio/699-lipo-rider-pro-fr.html">LiPo Rider Pro</a>, <a href="http://snootlab.com/lang-en/seeedstudio/702-panneau-solaire-3w-138x160-fr.html">SP 3W 138x160</a>, + 1 battery (<a href="https://hackspark.fr/en/catalogsearch/result/?q=lipo">another reseller</a>) - <a href="photos/labriqueinternet-solaire-details.png">Photo</a></li>
  </ul>

  <div class="pictures" id="boots">
    <a href="/img/boot1.png"><img src="/img/boot1_thumb.png" alt="Boot 1" /></a>
    <!-- <a href="/img/hardware.png"><img src="/img/hardware_thumb.png" alt="Hardware" /></a> -->
    <a href="/img/boot2.png"><img src="/img/boot2_thumb.png" alt="Boot 2" /></a>
  </div>

  <p>Cost of the hardware bundle describe above, per Cube (without the battery and the solar panel but including the shipping cost):</p>

  <ul>
    <li>Approximately 60€ as part of an associative bulk order (FFDN)</li>
    <li>Approximately 70€ as part of a personal bulk order (from 10 Cubes)</li>
    <li>Approximately 80€ otherwise</li>
  </ul>

  <p>Cube ornamentation and spreading the word:</p>

  <ul>
    <li>A <a href="stuff/internetcube-sticker.png">very nice sticker</a> (<a href="stuff/internetcube-sticker.svg">SVG</a>) to stick on an Olimex box (8cm x 5.5cm)</li>
    <li>A <a href="stuff/internetcube-poster-a3.png">beautiful poster</a> (<a href="stuff/internetcube-poster-a3.svg">SVG</a>) to stick on the walls (A3 format)</li>
  </ul>
</section>

<section id="replace-vpn-by-tor">
  <h2><span>Replacing the VPN</span> by Tor?</h2>

  <div class="text">
    <p>An extension to the cube is <a href="https://github.com/labriqueinternet/torclient_ynh">now available</a> (requires Wifi Hotspot) in order to offer an internet access via <a href="https://www.torproject.org">Tor</a>.</p>

    <p>The goal is to provide two Wifi networks: one with the VPN access and another one with the Tor access (and even a third for a PirateBox). It is distributed as a simple application for YunoHost. Activating this functionality is simple as enabling it in the YunoHost web interface.</p>

    <div class="pictures">
      <a href="/img/tor.png"><img src="/img/tor_thumb.png" alt="Tor" /></a>
    </div>

    <p>Then, every request to the Internet from the devices connected in Wifi are anonymised using the Tor network. However, to ensure real anonymity (political dissident, journalist, etc...) and prevent your browser from leaking informations about your identity, it is always recommended to directly use the <a href="https://www.torproject.org/download/download-easy.html">Tor Bundle</a> (only for the web and on your own computer). Furthermore, in accordance to the restrictions imposed by Tor, you Internet connection is not neutral (limited to TCP and UDP for DNS requests).</p>
  </div>
</section>

<section id="anonymity-and-law">
  <h2><span>Anonymity</span> and law?</h2>

  <p>Regarding the aspect « Internet access via VPN » : the associations of the FDN Federation (FFDN) in general don't guarantee anonymity in regard of the legal body, neither any impunity in regards of the law.</p>

  <p>The guarantee they bring at this level, is to only cooperate with the justice in the strictest framework of the law. Therefore, no data will be given away to anyone if the associated legal process is not strictly followed. We know that it's not always the case for the general public big access providers, that we can legitimately suspect them to provide informations on the bases of simple phone calls from police officers or to install privileged access to their data, outside of all legal process (which are nowadays becoming <a href="http://sous-surveillance.fr">more and more optional</a>...)</p>

  <p>VPN access can only guarantee anonymity regarding the French or Belgian legal body only if the provider is located in a country that is known to not collaborate easily with France/Belgium (for example Russia, but this will imply to trust the provider and the legislation of the country).</p>

  <p>But, no matter the country, setup the Cube with a foreign VPN provider (correctly chosen) will be especially interesting for a political dissident or a journalist who would like to protect himself against abuses from his country, to claim for more freedom.</p>
</section>

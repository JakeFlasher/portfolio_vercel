<template>
  <div class="container">
    <div id="name-container">
      <img id="avatar" src="./../assets/images/240kb.png" height="200" width="200" alt="avatar" />
      <h1>Chengao Shi</h1>
    </div>
    <div class="title-desc-container">
      <a id="github" href="https://github.com/JakeFlasher" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/github.svg" />Developer</a
      >
      <span>/</span>
      <a id="sspai" href="https://weixin.qq.com/f/EPGtx4Q50GV79hLsIm2dgS4" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/sspai.svg" />Climber</a
      >
      <span>/</span>
      <a id="blog" href="https://www.zhihu.com/follow" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/zeit.svg" />Blogger</a
      >
    </div>
    <div class="article">
      <h2>About Me</h2>
      <p>
        I'm <i>Chengao SHI</i> born in Suzhou, China, a dedicated coder & climber currently pursuing my PhD degree at <i>The Hong Kong University of Science and Technology</i>(HKUST), supervised by <i>Prof.Jiang XU</i>, in <a href="https://eexu.home.ece.ust.hk/BDSL.html" target="_blank" rel="noopener noreferrer">BDSL</a> team. 

        
        <!-- <i>spencerwoo</i>. Some other variations:
        <a href="https://twitter.com/realSpencerWoo" target="_blank" rel="noopener noreferrer">@realSpencerWoo</a> /
        <a href="https://weibo.com/spencerwoo" target="_blank" rel="noopener noreferrer">@SpencerWoo</a> /
        <a href="https://github.com/spencerwooo" target="_blank" rel="noopener noreferrer">@spencerwooo</a>. You may
        know me from GitHub / Jike / SSPAI or other places. Yes, those are also me. -->
      </p>

      <h2>Academics</h2>
      <ul>
        <li>
          🙇 Postgraduate student at HKUST (🇭🇰
          <a href="https://hkust.edu.hk/home" target="_blank" rel="noopener noreferrer">HKUST</a>), 2021-Fall
          entry,
          <i
            ><a
              href="https://ece.hkust.edu.hk/phdeas"
              target="_blank"
              rel="noopener noreferrer"
              >PhD(EAS) in ECE</a
            ></i
          >.
        </li>
        <li>
          🍭 XJTU Alumni, <a href="/hyouth" target="_blank" rel="noopener noreferrer">The Honors Youth Program</a>(🇨🇳
          <a href="http://www.xjtu.edu.cn/" target="_blank" rel="noopener noreferrer">Xi'an Jiaotong University</a
          >), <i>BSc in CS</i>.
        </li>
        <li>🔭 <b>Fields of interest: </b> Computer Systems and Architecture.</li>
      </ul>

      <h2>Experiences</h2>
      <ul>
        <li>⚫ Arch Linux Laptop / KDE Ubuntu Desktop </li>
        <li>🔵 iPhone 12 ProMax</li>
      </ul>

      <h2>For more info</h2>
      <p>
        I have verified my identity with a GPG signature which proves my ownership of this domain. (See the cryptography
        proof here:
        <a
          href="http://keybase.io/spencerwoo/sigchain#abb6f40f8c804e7411e91544b7cdb8e011df8e6f84dcd0b709f848f85dc6248d0f"
          target="_blank"
          rel="noopener noreferrer"
          >Keybase - claimed ownership of <b>spencerwoo.com</b> via dns</a
        >.) In other words, <i>I AM LEGIT HERE.</i>
      </p>
      <p>
        I have my GPG public key hosted on
        <a href="http://keybase.io/spencerwoo" target="_blank" rel="noopener noreferrer">Keybase - spencerwoo</a>. You
        can pull and import my GPG public key with:
      </p>
      <pre>curl https://keybase.io/spencerwoo/pgp_keys.asc | gpg --import</pre>

      <h2>Contacts</h2>
      <ul>
        <li>
          <b>Email：</b>
          <a href="mailto:cshiai@connect.ust.hk">cshiai#connect.ust.hk</a><i> (Preferred)</i>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="css" scoped>
#name-container {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
}

#avatar {
  width: 42px;
  height: 42px;
  border-radius: 50%;
  margin-right: 12px;
}

#copyright:hover {
  border: none;
}

.title-font {
  width: 16px;
  height: 16px;
  margin-right: 4px;
}

.title-desc-container {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  margin: 8px 0;
}

.title-desc-container a {
  display: flex;
  align-items: center;
}

.title-desc-container span {
  margin: 0px 4px;
}

.title-desc-container #github {
  color: #24292e;
}

.title-desc-container #sspai {
  color: #ca2c2a;
}

.title-desc-container #blog {
  color: #0070f3;
}
</style>


<template>
  <div>
    <div class="container">
      <h1>2. Dialogflow</h1>
      <p>
        AdaLoveBot uses machine learning platform named as Dialogflow. All our requests are
        processed through them. Follow the following steps:
      </p>
      <ol>
        <li>Create an account on dialogflow with your email address.</li>
        <li>Create a new agent. Name it anything you want.</li>
        <li>Fork and clone the <a href="https://github.com/openwisp/AdaLoveBot-intents">repository</a>.</li>
        <li>Create a zip file for all the files under <code>agent</code> directory.</li>
        <li>Go to your agent settings on dialogflow. Click on <code>Export and Import</code>. Select <code>Restore from zip</code> and choose your zip file.</li>
      </ol>
    </div>
    <div class="slider">
      <nuxt-link to="/1"><div class="previous"><i class="fa fa-arrow-circle-left"></i></div></nuxt-link>
      <nuxt-link to="/3"><div class="next"><i class="fa fa-arrow-circle-right"></i></div></nuxt-link>
    </div>
  </div>
</template>

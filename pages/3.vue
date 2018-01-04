<template>
  <div>
    <div class="container">
      <h1>3. Setup <code>.env</code> file</h1>
      <p>
        Under the repository you have just forked, you need to setup <code>.env</code> file.
        This file stores all you API Keys.
      </p>
      <p>
        In the <code>.env</code> file, put your keys as follows.
      </p>
      <pre>
        <code>
          APIAI_TOKEN=your_dialogflow_client_token
          GITTER_TOKEN=your_gitter_developer_token
          ROOM=your_bot_testing_room_id
          USER_ID=your_bot_user_id
        </code>
      </pre>
      <p>
        In the above file, you will have to find your ROOM and USER_ID by running following CURL commands.
      </p>
      <pre>curl -i -H "Accept: application/json" -H "Authorization: Bearer :your_gitter_developer_token:" "https://api.gitter.im/v1/rooms"</pre>
      <p>
        Copy the ID of the room that you created. Put this ID in ROOM id. Next run following:
      </p>
      <pre>curl -i -H "Accept: application/json" -H "Authorization: Bearer :your_gitter_developer_token:" "https://api.gitter.im/v1/rooms/:your_bot_testing_room_id:/users"</pre>
      <p>
        Copy the user id that comes for your bot name.
      </p>
    </div>
    <div class="slider">
      <nuxt-link to="/2"><div class="previous"><i class="fa fa-arrow-circle-left"></i></div></nuxt-link>
      <nuxt-link to="/4"><div class="next"><i class="fa fa-arrow-circle-right"></i></div></nuxt-link>
    </div>
  </div>
</template>

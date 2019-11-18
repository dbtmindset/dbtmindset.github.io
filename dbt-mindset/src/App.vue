<template>
  <div id="app">
    <div class="title">
      <h1>DBT Mindset</h1>
    </div>
    <div class="items">
      <h2><a href="/flashcards/">DBT Flashcards</a></h2>
    </div>
    <div class="content">
      <wordcloud
        :data="defaultWords"
        nameKey="name"
        valueKey="value"
        :showTooltip="true"
        :color="myColors"
        >
      </wordcloud>
    </div>
  </div>
</template>

<script>
import wordcloud from 'vue-wordcloud'

export default {
  name: 'app',
  components: {
    wordcloud
  },
  mounted() {
  },
  data() {
    return {
      myColors: ['#ffffff'],
      defaultWords: [
  {
    "name": "mind",
    "value": 247
  },
  {
    "name": "person",
    "value": 213
  },
  {
    "name": "emotion",
    "value": 189
  },
  {
    "name": "about",
    "value": 146
  },
  {
    "name": "emotions",
    "value": 139
  },
  {
    "name": "others",
    "value": 134
  },
  {
    "name": "thoughts",
    "value": 132
  },
  {
    "name": "behavior",
    "value": 123
  },
  {
    "name": "skills",
    "value": 107
  },
  {
    "name": "regulation",
    "value": 107
  },
  {
    "name": "people",
    "value": 107
  },
  {
    "name": "something",
    "value": 99
  },
  {
    "name": "notice",
    "value": 98
  },
  {
    "name": "facts",
    "value": 98
  },
  {
    "name": "being",
    "value": 97
  },
  {
    "name": "body",
    "value": 96
  },
  {
    "name": "mindfulness",
    "value": 94
  },
  {
    "name": "will",
    "value": 92
  },
  {
    "name": "practice",
    "value": 88
  },
  {
    "name": "feel",
    "value": 86
  },
  {
    "name": "someone",
    "value": 84
  },
  {
    "name": "effectiveness",
    "value": 83
  },
  {
    "name": "distress",
    "value": 83
  },
  {
    "name": "feeling",
    "value": 82
  },
  {
    "name": "situation",
    "value": 80
  },
  {
    "name": "change",
    "value": 79
  },
  {
    "name": "tolerance",
    "value": 76
  },
  {
    "name": "thinking",
    "value": 76
  },
  {
    "name": "interpersonal",
    "value": 76
  },
  {
    "name": "step",
    "value": 75
  },
  {
    "name": "attention",
    "value": 73
  },
  {
    "name": "life",
    "value": 72
  },
  {
    "name": "ask",
    "value": 70
  },
  {
    "name": "time",
    "value": 69
  },
  {
    "name": "doing",
    "value": 69
  },
  {
    "name": "see",
    "value": 68
  },
  {
    "name": "opposite",
    "value": 68
  },
  {
    "name": "take",
    "value": 66
  },
  {
    "name": "feelings",
    "value": 65
  },
  {
    "name": "try",
    "value": 60
  },
  {
    "name": "action",
    "value": 60
  },
  {
    "name": "events",
    "value": 59
  },
  {
    "name": "actions",
    "value": 58
  },
  {
    "name": "effective",
    "value": 57
  },
  {
    "name": "wise",
    "value": 56
  },
  {
    "name": "love",
    "value": 56
  },
  {
    "name": "like",
    "value": 56
  },
  {
    "name": "use",
    "value": 55
  },
  {
    "name": "more",
    "value": 55
  },
  {
    "name": "keep",
    "value": 55
  },
  {
    "name": "important",
    "value": 53
  },
  {
    "name": "breathing",
    "value": 52
  },
  {
    "name": "breath",
    "value": 52
  },
  {
    "name": "imagine",
    "value": 51
  }
]
,
    }
  },
  methods: {
  },

}
</script>

<style>

body, html {
  height: 100%;
  margin: 0;
  padding: 0;
}
#app {
  margin: 0px;
  padding: 25px;
  height: 100%;
  color: white;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("https://github.com/dbtmindset/dbtmindset.github.io/raw/master/fog-rock-stack.jpg");
}
.title {
  text-align: center;
  padding-top: 20px;
}
.items {
  text-align: center;
}
.content {
  margin-left:100px;
}
a:link {
  color: white;
}
a:visited {
  color: gray;
}
a:hover {
  color: gray;
}
a:active {
  color: white;
}

</style>

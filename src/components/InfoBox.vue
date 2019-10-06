<template>
  <div>
    <h1>Frequently asked Questions</h1>
    <v-expansion-panels multiple>
      <v-expansion-panel>
        <v-expansion-panel-header>What is omegaboot.com?</v-expansion-panel-header>
        <v-expansion-panel-content>
          Omegaboot is a kahoot bot made by
          <a
            href="https://github.com/idiidk"
            target="_blank"
          >@idiidk</a> and is kindly made open source on
          <a
            href="https://github.com/idiidk/kahoot-tools"
            target="_blank"
          >GitHub</a>.
          Although kahoot bots can be annoying for teachers, it is undoubtedly a fun attraction for players as hundreds of bots spontaneously join and flood the kahoot causing confusion and chaos in the class. Omegaboot replicates this experience by providing users with a tool that can add hudreds (if not thousands) of bots in just a couple of clicks to create havoc during a kahoot quiz.
        </v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>Why was omegaboot created?</v-expansion-panel-header>
        <v-expansion-panel-content>Omegaboot has existed for nearly a year now in hopes of providing a better experience and functionality than other kahoot bots. The saturated market was filled with bots that charged money for the answer correctly feature (which was developed by @idiidk himself but later copied and monetised) and bots with small limits (100 or 200 bots). We wanted to disrupt the kahoot bot market by bringing new features and better UI and mobile support and all of this completely free! We are greatful for the recent popularity of our bot and we promise all of our features will be completely free.</v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>How does all of this work?</v-expansion-panel-header>
        <v-expansion-panel-content>
          In short, when you enter the pin and a name on our website it replicates requests made if you would join a kahoot from the official kahoot.it website, therefore our bots are indistinguishable from real players which is why they are so hard to detect. Efforts have been made by kahoot to prevent bots in games by adding 2FA (having to enter a code on the kahoot screen as well a pin) as mentioned in their
          <a
            href="https://support.kahoot.com/hc/en-us/community/posts/360018898273-Bot-Protection"
            target="_blank"
          >blog post</a> but these measures can be circumvented by trying all the possible 2FA combinations to brute force the code.
        </v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>What are all the features?</v-expansion-panel-header>
        <v-expansion-panel-content>Our bot has a comprehensive list of features which are not found elsewhere. For example we have an option to search the kahoot website for public quizzes matching the one being played. Then the results are parsed and displayed on our website, which include the answers to all the questions! Other features include the ability to make the bots answer specific answers (in kahoot you choose from a maximum of four colors on you screen which correspond to answers to the question being displayed, sometimes more than one answer can be correct), or even a feature to choose a random answer for each bot. We also have some experimental features which are created from bugs in kahoot, but can be patched any some so I won't be listing them here. And don't forget, the ability to add thousands of bots! You can also install our website as an app if you use chrome by clicking the plus icon in the url bar, you can also do this on some android phones.</v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>How do I use it?</v-expansion-panel-header>
        <v-expansion-panel-content>
          Here's a cool if showing how to use it:
          <v-img
            src="https://cdn.discordapp.com/attachments/567265256229830659/625258456433295371/68747470733a2f2f69646969646b2e6170702f6b61686f6f742d746f6f6c732e676966.gif"
          ></v-img>
        </v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>Is it safe to use?</v-expansion-panel-header>
        <v-expansion-panel-content>Apart from the ethical issues of from being able to look at the answer of the quiz (if it's public), the bot completely anonymous meaning it can't be traced to you (unless you use a school laptop/computer, then teachers can see that you visited this site so we recommend using a phone as the website is fully optimized for mobile. You can install it as an app too!). But be careful as teachers tend to get angry and will investigate the mysterious appearance of players on their quiz, so try not to cause any attantion to yourself!</v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>Why do people use kahoot bots/spammers/crashers?</v-expansion-panel-header>
        <v-expansion-panel-content>
          As said by an
          <a
            href="https://support.kahoot.com/hc/en-us/community/posts/360018898273-Bot-Protection?page=1#community_comment_360002697334"
            target="_blank"
          >official reply</a> by Kahoot, "students tend to use bot services if they feel that the gameplay is too challenging". The novelty of adding bots could also contribute to it but we have no definitive answer but we are interested in this too! Some time soon we wish to conduct a survey of our userbase to find the reason why people use bots as it would be interesting for both us and Kahoot with a prospect of making kahoot more enjoyable for everyone!
        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
  </div>
</template>

<script>
export default {
  name: "InfoBox"
};
</script>
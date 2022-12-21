<template>
  <div class="section-container">Professional Experience</div>
  <div class="section-content full">
    <div class="experience-title-container">
      <div class="company">Global Payments</div>
      <span>&nbsp;-&nbsp;</span>
      <div class="role">Software Engineer II</div>
      <span>&nbsp;;&nbsp;</span>
      <div class="city">Chengdu City, CN</div>

      <div class="time-range">July 2022 - Feb 2023</div>
    </div>
  </div>
  <div class="section-content full experience">
    <ul>
      <li>
        Maintained a massive in-house web application that built by AngularJS
        and Dynamic Form. Built and maintained an internal UI Share Library
        which also used AngularJS.
      </li>
      <li>
        Promised the high quality of codebase. Worked with Bitbucket to do Code
        Review from members' PR. The crash rate of our project in production is
        as low as 0.00001%.
      </li>
      <li>
        Collaborated with some international dev teams from Ukraine, US, etc.
      </li>
      <li>
        Worked in Agile Development. Followed the SCRUM Flow. Used Sprint to
        drive daily work.
      </li>
    </ul>
  </div>
</template>

<style scoped>
.full {
  width: 100%;
}
.experience-title-container {
  position: relative;
  display: flex;
  align-items: center;
}
.company {
  font-size: 18px;
  font-weight: bolder;
}
.role {
  font-size: 16px;
  font-style: italic;
}
.time-range {
  position: absolute;
  top: 0;
  right: 0;
  font-style: italic;
}
.experience {
  margin-top: 2mm;
}
ul {
  list-style-type: square;
  margin-left: 4mm;
  line-height: 1.5em;
}
</style>

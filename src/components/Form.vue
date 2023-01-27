<template>
  <!-- Form section -->
  <div class="aside">
    <div class="form">
      <h2>Contact Information</h2>
      <label for="name">First and Last Name:</label>
      <input type="text" v-model="name" /><br />
      <label for="website">Portfolio website if any</label>
      <input type="text" v-model="website" /><br />
      <label for="email">Email Address:</label>
      <input type="email" v-model="email" /><br />
      <label for="phone">Phone Number</label>
      <input type="text" v-model="phone" /><br />
      <label for="location">Location/City & Country</label>
      <input type="text" v-model="location" /><br />
      <label for="linkedin">Linkedin Profile</label>
      <input type="text" v-model="linkedin" /><br />
      <label for="twitter">Twitter Profile</label>
      <input type="text" v-model="twitter" />
    </div>

    <div class="form">
      <h2>Education</h2>
      <label for="course">Course/Certificate Name</label>
      <input type="text" v-model="course" /><br />
      <label for="school">University/College/School</label>
      <input type="text" v-model="school" /><br />
      <label for="yearOfStart">Date Started</label>
      <input type="text" v-model="yearOfStart" /><br />
      <label for="yearOfGrad">Date Ended</label>
      <input type="text" v-model="yearOfGrad" /><br />
      <label for="schoolLocation">City/Country</label>
      <input type="text" v-model="schoolLocation" /><br />
    </div>

    <div class="form">
      <h2>Skills</h2>
      <label for="skill1">Skill 1</label>
      <input type="text" v-model="skill1" /><br />
      <label for="skill2">Skill 2</label>
      <input type="text" v-model="skill2" /><br />
      <label for="skill3">Skill 3</label>
      <input type="text" v-model="skill3" /><br />
      <label for="skill4">Skill 4</label>
      <input type="text" v-model="skill4" /><br />
      <label for="skill5">Skill 5</label>
      <input type="text" v-model="skill5" /><br />
      <label for="skill6">Skill 6</label>
      <input type="text" v-model="skill6" /><br />
      <label for="skill7">Skill 7</label>
      <input type="text" v-model="skill7" /><br />
      <label for="skill8">Skill 8</label>
      <input type="text" v-model="skill8" /><br />
      <label for="skill9">Skill 9</label>
      <input type="text" v-model="skill9" /><br />
      <label for="skill10">Skill 10</label>
      <input type="text" v-model="skill10" /><br />
    </div>

    <div class="form">
      <h2>Career Objective</h2>
      <label for="objectives">Profile Summary</label><br />
      <textarea type="text" v-model="objectives"></textarea>
    </div>
  </div>
</template>

<script>
export default {
  name: "ResumeAppForm",

  data() {
    return {
      name: "",
      website: "",
      email: "",
      phone: "",
      location: "",
      linkedin: "",
      twitter: "",
      course: "",
      school: "",
      yearOfStart: "",
      yearOfGrad: "",
      schoolLocation: "",
      skills: "",
      profileSummary: "",
      jobTitle: "",
      company: "",
      yearStarted: "",
      yearFinished: "",
      workLocation: "",
      responsibility: "",
      skill1: "",
      skill2: "",
      skill3: "",
      skill4: "",
      skill5: "",
      skill6: "",
      skill7: "",
      skill8: "",
      skill9: "",
      skill10: "",
      objectives: "",
    };
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
.aside {
  margin: 20px;
  padding: 10px;
  background: rgba(209, 215, 221, 0.4);
}

label {
  margin-right: 10px;
}

input[type="text" i] {
  width: 100%;
}
input[type="email" i] {
  width: 100%;
}
textarea[type="text" i] {
  width: 100%;
}

.form {
  margin-bottom: 20px;
  padding: 10px;
  /* display: block; */
}
</style>
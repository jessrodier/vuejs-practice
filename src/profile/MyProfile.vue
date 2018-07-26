<template>
  <div>
    <div class="top-row">
      <div class="top part">
        <!-- <img :src="selectedRobot.head.src" title="head"/> -->
        <!-- <button @click="selectPreviousHead()" class="prev-selector">&#9668;</button> -->
        <!-- <button @click="selectNextHead()" class="next-selector">&#9658;</button> -->
        <h2>hello world.</h2>
        <ul>
          <li>userData.admins[0]</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import userData from '../data/users';

// function getPreviousValidIndex(index, length) {
//   const deprecatedIndex = index - 1;
//   return deprecatedIndex < 0 ? length - 1 : deprecatedIndex;
// }

// function getNextValidIndex(index, length) {
//   const incrementedIndex = index + 1;
//   return incrementedIndex > length - 1 ? 0 : incrementedIndex;
// }

export default {
  name: 'RobotBuilder',
  data() {
    return {
      // availableParts,
      // selectedHeadIndex: 0,
      // selectedLeftArmIndex: 0,
      // selectedTorsoIndex: 0,
      // selectedRightArmIndex: 0,
      // selectedBaseIndex: 0,
    };
  },
  computed: {
    selectedRobot() {
      return {
        // head: availableParts.heads[this.selectedHeadIndex],
        // leftArm: availableParts.arms[this.selectedLeftArmIndex],
        // torso: availableParts.torsos[this.selectedTorsoIndex],
        // rightArm: availableParts.arms[this.selectedRightArmIndex],
        // base: availableParts.bases[this.selectedBaseIndex],
      };
    },
  },
  methods: {
    // selectNextHead() {
    //   this.selectedHeadIndex =
    //     getNextValidIndex(this.selectedHeadIndex, availableParts.heads.length);
    // },
    // selectPreviousHead() {
    //   this.selectedHeadIndex =
    //     getPreviousValidIndex(this.selectedHeadIndex, availableParts.heads.length);
    // },
  },
};
</script>

<style>

</style>

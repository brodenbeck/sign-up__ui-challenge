<template>
  <svg :class="className" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20.13 16.73">
    <title>Cloud Upload by Storm Icons from the Noun Project</title>
    <g id="Layer_2" data-name="Layer 2">
      <g id="Layer_1-2" data-name="Layer 1">
        <path
          d="M13.17,11,10.45,8.32a.55.55,0,0,0-.77,0L7,11a.55.55,0,0,0,.39.93.54.54,0,0,0,
          .38-.16L9.52,10v6.17a.55.55,0,0,0,.55.54.54.54,0,0,0,.54-.54V10l1.79,1.79a.54.54,0,0,0,
          .39.16.51.51,0,0,0,.38-.16A.55.55,0,0,0,13.17,11Z"
          :fill="color"
        />
        <path
          d="M16,5.47A6,6,0,0,0,4.08,6a5.76,5.76,0,0,0,.06.82h-.2a3.95,3.95,0,0,0,0,
          7.89H7.35a.54.54,0,0,0,.54-.54.55.55,0,0,0-.54-.55H4A2.86,2.86,0,1,1,4,7.89a2.74,2.74,0,
          0,1,.74.1.54.54,0,0,0,.67-.67A4.82,4.82,0,0,1,5.17,6,4.9,4.9,0,0,1,15,6a.55.55,0,0,0,
          .55.55,3.54,3.54,0,0,1,0,7.07H12.79a.55.55,0,0,0-.55.55.55.55,0,0,0,.55.54h2.72A4.62,
          4.62,0,0,0,16,5.47Z"
          :fill="color"
        />
      </g>
    </g>
  </svg>
</template>

<script>
export default {
  name: 'UploadIcon',
  props: {
    color: {
      type: String,
      default: '#53D8FB',
    },
    className: {
      type: String,
      default: '',
    },
  },
  data() {
    return {};
  },
};
</script>

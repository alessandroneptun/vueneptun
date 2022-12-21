<template>
    <div class="div" :maxWidth="1200" :lazyLoad="false">
      <section class="section">
        <div class="div-2" :lockAspectRatio="false" :noWebp="true">
          <picture
            ><img
              loading="lazy"
              src="https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e"
              srcset="
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e?width=100   100w,
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e?width=200   200w,
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e?width=400   400w,
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e?width=800   800w,
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e?width=1200 1200w,
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e?width=1600 1600w,
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e?width=2000 2000w,
                https://cdn.builder.io/api/v1/image/assets%2Fce87ed5c9ee04f559c496ec1cc117ab8%2Ffc10e78116fd4d02b62670d8cb20cb1e
              "
              class="image"
          /></picture>
          <div class="builder-image-sizer image-sizer"></div>
        </div>
      </section>
    </div>
  </template>
  
  <script>
  export default {
    name: "my-component",
  };
  </script>
  
  <style scoped>
  .div {
    display: flex;
    flex-direction: column;
    position: relative;
    margin-top: 0px;
    padding-left: 24px;
    padding-right: 24px;
    padding-top: 0px;
    padding-bottom: 0px;
    background-color: rgba(0, 0, 0, 1);
    width: 100%;
    height: 63px;
  }
  .section {
    width: 100%;
    align-self: stretch;
    flex-grow: 1;
    max-width: 1200px;
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
  }
  .div-2 {
    display: flex;
    flex-direction: column;
    position: relative;
    margin-top: auto;
    width: 180px;
    min-height: 20px;
    min-width: 20px;
    overflow: hidden;
    margin-bottom: auto;
  }
  .image {
    object-fit: cover;
    object-position: center;
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0;
    left: 0;
  }
  .image-sizer {
    width: 100%;
    padding-top: 12.7%;
    pointer-events: none;
    font-size: 0;
  }
  </style>
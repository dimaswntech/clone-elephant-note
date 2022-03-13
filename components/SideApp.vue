<template>
  <div class="side_app md:max-w-sm md:w-1/6 top-0">
    <div class="side_app_box static w-auto overflow-hidden flex flex-col">
      <div class="side_logo mt-10 ml-6">
        <div class="logo_box">
          <div>
            <nuxt-link to="#" class="flex items-center">
              <div>
                <img
                  class="side_logo_img mr-4"
                  src="https://www.seekpng.com/png/full/69-695584_vector-format-logos-21st-world-congress-on-psychology.png"
                  alt=""
                />
              </div>
              <span class="elephant-text font-semibold text-3xl"
                >Elep<span style="color: #e6c689">hant</span></span
              >
            </nuxt-link>
          </div>
        </div>
      </div>

      <div class="nav_side ml-4 mt-14 flex-auto min-w-0 max-w-full">
        <ul>
          <li class="mb-1.5">
            <div class="li_box">
              <nuxt-link to="#" class="">
                <div
                  class="li_box_item flex items-center"
                  style="background-color: rgba(39, 68, 45, 0.349)"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-house-door"
                    viewBox="0 0 16 16"
                  >
                    <path
                      d="M8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4.5a.5.5 0 0 0 .5-.5v-4h2v4a.5.5 0 0 0 .5.5H14a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146zM2.5 14V7.707l5.5-5.5 5.5 5.5V14H10v-4a.5.5 0 0 0-.5-.5h-3a.5.5 0 0 0-.5.5v4H2.5z"
                    />
                  </svg>
                  <span class="li_nav_text text-lg">Home</span>
                </div>
              </nuxt-link>
            </div>
          </li>
          <li class="mb-1.5">
            <div class="li_box">
              <nuxt-link to="#" class="">
                <div class="li_box_item flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-calendar3"
                    viewBox="0 0 16 16"
                  >
                    <path
                      d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"
                    />
                    <path
                      d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"
                    />
                  </svg>
                  <span class="li_nav_text text-lg">Calendar</span>
                </div>
              </nuxt-link>
            </div>
          </li>
          <li class="mb-1.5">
            <div class="li_box">
              <nuxt-link to="#" class="">
                <div class="li_box_item flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-calendar2-plus"
                    viewBox="0 0 16 16"
                  >
                    <path
                      d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM2 2a1 1 0 0 0-1 1v11a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V3a1 1 0 0 0-1-1H2z"
                    />
                    <path
                      d="M2.5 4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5V4zM8 8a.5.5 0 0 1 .5.5V10H10a.5.5 0 0 1 0 1H8.5v1.5a.5.5 0 0 1-1 0V11H6a.5.5 0 0 1 0-1h1.5V8.5A.5.5 0 0 1 8 8z"
                    />
                  </svg>
                  <span class="li_nav_text text-lg">Shared</span>
                </div>
              </nuxt-link>
            </div>
          </li>
          <li class="mb-1.5">
            <div class="li_box">
              <nuxt-link to="#" class="">
                <div class="li_box_item flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-sliders"
                    viewBox="0 0 16 16"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M11.5 2a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zM9.05 3a2.5 2.5 0 0 1 4.9 0H16v1h-2.05a2.5 2.5 0 0 1-4.9 0H0V3h9.05zM4.5 7a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zM2.05 8a2.5 2.5 0 0 1 4.9 0H16v1H6.95a2.5 2.5 0 0 1-4.9 0H0V8h2.05zm9.45 4a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zm-2.45 1a2.5 2.5 0 0 1 4.9 0H16v1h-2.05a2.5 2.5 0 0 1-4.9 0H0v-1h9.05z"
                    />
                  </svg>
                  <span class="li_nav_text text-lg">Setting</span>
                </div>
              </nuxt-link>
            </div>
          </li>
        </ul>
      </div>
      <div class="profile_box w-1/6 px-10 mb-10">
        <nuxt-link to="#" class="fill_profile flex">
          <div class="profile_img">
            <img src="../assets/img/logo.png" style="width: 50px" alt="" />
          </div>
          <div class="profile_text flex flex-col text-sm ml-6 items-center">
            <div class="mt-1 text-white">
              <p>Gokla</p>
              <p>Krusnyev</p>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.side_app {
  background-color: #477468;
  /* background-image: url('../assets/img/preview.jpg'); */
  /* mix-blend-mode: multiply; */
}
.side_logo_img {
  width: 38px;
}
.elephant-text {
  color: white;
}
.li_box_item {
  color: white;
  padding-top: 15px;
  padding-bottom: 15px;
  background-color: transparent;
  border-top-left-radius: 15px;
  border-bottom-left-radius: 15px;
  transition: all 0.5s;
}
.li_box_item:hover {
  color: white;
  padding-top: 15px;
  padding-bottom: 15px;
  background-color: rgba(39, 68, 45, 0.349);
}
.li_box_item svg {
  width: 23px;
  height: 23px;
  margin-left: 24px;
  margin-right: 12px;
}
.profile_box {
  position: absolute;
  bottom: 0;
}
.fill_profile {
  background-color: rgba(231, 251, 233, 0.267);
  border-radius: 15px;
  padding: 10px;
  transition: all 0.3s;
}
.fill_profile:hover {
  background-color: rgba(255, 255, 255, 0.472);
  border-radius: 15px;
}
</style>

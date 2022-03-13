<template>
  <div class="base_app flex flex-auto md:w-4/6 flex-col">
    <div class="side_one mt-10 mb-8">
      <div class="side_one__fill flex px-8">
        <div class="side_one__text flex flex-auto">
          <span>All Ideas</span>
        </div>
        <div class="side_one__icon flex flex-row">
          <div class="trash_icon mr-12">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="16"
              height="16"
              fill="currentColor"
              class="bi bi-trash3"
              viewBox="0 0 16 16"
            >
              <path
                d="M6.5 1h3a.5.5 0 0 1 .5.5v1H6v-1a.5.5 0 0 1 .5-.5ZM11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3A1.5 1.5 0 0 0 5 1.5v1H2.506a.58.58 0 0 0-.01 0H1.5a.5.5 0 0 0 0 1h.538l.853 10.66A2 2 0 0 0 4.885 16h6.23a2 2 0 0 0 1.994-1.84l.853-10.66h.538a.5.5 0 0 0 0-1h-.995a.59.59 0 0 0-.01 0H11Zm1.958 1-.846 10.58a1 1 0 0 1-.997.92h-6.23a1 1 0 0 1-.997-.92L3.042 3.5h9.916Zm-7.487 1a.5.5 0 0 1 .528.47l.5 8.5a.5.5 0 0 1-.998.06L5 5.03a.5.5 0 0 1 .47-.53Zm5.058 0a.5.5 0 0 1 .47.53l-.5 8.5a.5.5 0 1 1-.998-.06l.5-8.5a.5.5 0 0 1 .528-.47ZM8 4.5a.5.5 0 0 1 .5.5v8.5a.5.5 0 0 1-1 0V5a.5.5 0 0 1 .5-.5Z"
              />
            </svg>
          </div>
          <div class="mag_icon">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="16"
              height="16"
              fill="currentColor"
              class="bi bi-search"
              viewBox="0 0 16 16"
            >
              <path
                d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"
              />
            </svg>
          </div>
        </div>
      </div>
    </div>
    <div class="side_two">
      <ul class="side_two__fill">
        <li class="fill_task max-w-full">
          <div class="fill__task py-6 px-6 flex flex-col">
            <div class="flex">
              <span class="title_task text-lg font-semibold flex-auto"
                >Everyday Work Hard</span
              >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="clip_svg bi bi-paperclip mr-4"
                viewBox="0 0 16 16"
              >
                <path
                  d="M4.5 3a2.5 2.5 0 0 1 5 0v9a1.5 1.5 0 0 1-3 0V5a.5.5 0 0 1 1 0v7a.5.5 0 0 0 1 0V3a1.5 1.5 0 1 0-3 0v9a2.5 2.5 0 0 0 5 0V5a.5.5 0 0 1 1 0v7a3.5 3.5 0 1 1-7 0V3z"
                />
              </svg>
            </div>
            <div class="desc_task flex mt-2">
              <span class="flex-auto font-medium"
                >Work hard everyday until i success</span
              >
              <span>23 min ago</span>
            </div>
          </div>
        </li>
        <li class="fill_task max-w-full" style="background-color: #fff">
          <div class="fill__task py-6 px-6 flex flex-col">
            <span class="title_task text-lg font-semibold"
              >Everyday Work Hard</span
            >
            <div class="desc_task flex mt-2">
              <span class="flex-auto font-medium"
                >Work hard everyday until i success</span
              >
              <span>23 min ago</span>
            </div>
          </div>
        </li>
        <li class="fill_task max-w-full">
          <div class="fill__task py-6 px-6 flex flex-col">
            <div class="flex">
              <span class="title_task text-lg font-semibold flex-auto"
                >Everyday Work Hard</span
              >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="clip_svg bi bi-paperclip mr-4"
                viewBox="0 0 16 16"
              >
                <path
                  d="M4.5 3a2.5 2.5 0 0 1 5 0v9a1.5 1.5 0 0 1-3 0V5a.5.5 0 0 1 1 0v7a.5.5 0 0 0 1 0V3a1.5 1.5 0 1 0-3 0v9a2.5 2.5 0 0 0 5 0V5a.5.5 0 0 1 1 0v7a3.5 3.5 0 1 1-7 0V3z"
                />
              </svg>
            </div>
            <div class="desc_task flex mt-2">
              <span class="flex-auto font-medium"
                >Work hard everyday until i success</span
              >
              <span>23 min ago</span>
            </div>
          </div>
        </li>
        <li class="fill_task max-w-full">
          <div class="fill__task py-6 px-6 flex flex-col">
            <span class="title_task text-lg font-semibold"
              >Everyday Work Hard</span
            >
            <div class="desc_task flex mt-2">
              <span class="flex-auto font-medium"
                >Work hard everyday until i success</span
              >
              <span>23 min ago</span>
            </div>
          </div>
        </li>
      </ul>
    </div>
    <div class="side_three absolute bottom-0 px-32 mb-8">
      <div class="box_add flex justify-center items-center">
        <nuxt-link to="#" class="fill_create flex inline-block">
          <div class="icon_create mr-4">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="27"
              height="27"
              fill="white"
              class="bi bi-plus-circle-fill"
              viewBox="0 0 16 16"
            >
              <path
                d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.5 4.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3z"
              />
            </svg>
          </div>
          <span class="font-semibold">Add New Ideas</span>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.side_two {
  border-top: 1px solid #f3f4f6;
}
.side_one__text span {
  font-size: 25px;
}
.trash_icon svg {
  color: #88898c;
  width: 25px;
  height: 25px;
}
.mag_icon svg {
  color: #88898c;
  width: 25px;
  height: 25px;
}
.side_two {
  max-height: 500px;
}
.fill_task {
  border-bottom: 1px solid #f3f4f6;
}
.title_task {
  color: #3f4144;
}
.desc_task {
  color: #88898c;
}
.clip_svg {
  color: #88898c;
  width: 25px;
  height: 25px;
  transform: rotate(50deg);
}
.side_three {
  width: 83%;
}
.box_add {
  border: 2px dashed #88898c;
  border-radius: 15px;
  height: 100px;
}
.fill_create {
  color: #88898c;
}
</style>

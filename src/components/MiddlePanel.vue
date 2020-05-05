<template>
  <div class="block w-1/2">
    <div class="px-4 py-2 border-b-2 border-gray-400 text-sm">
      <span class="text-secondary"><a href="#">Contacts</a></span>
      <span class="mx-2">></span>
      <span class="text-secondary"><a href="#">User</a></span>
      <span class="mx-2">></span>
      <span>Properties</span>
    </div>
    <div class="px-4 mt-2">
      <!-- Heading section -->
      <div class="flex text-secondary items-center">
        <div>
          <svg
            class="fill-current"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            width="24"
            height="24"
          >
            <path
              class="heroicon-ui"
              d="M13 20v-5h-2v5a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-7.59l-.3.3a1 1 0 1 1-1.4-1.42l9-9a1 1 0 0 1 1.4 0l9 9a1 1 0 0 1-1.4 1.42l-.3-.3V20a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2zm5 0v-9.59l-6-6-6 6V20h3v-5c0-1.1.9-2 2-2h2a2 2 0 0 1 2 2v5h3z"
            />
          </svg>
        </div>
        <h1 class="ml-2 pt-1 text-xl uppercase text-gray-800">Details User</h1>
        <div
          class="bg-secondary text-white px-4 py-1 mt-1 rounded-full text-xs uppercase tracking-wide ml-2 font-semibold"
        >
          Active
        </div>
      </div>
      <div class="text-sm mb-3">
        123 Main St., Galveston, TX 77555
      </div>
    </div>
    <!-- Details section -->
    <div
      class="bg-white border border-primary border-t-4 border-b-0 border-l-0 border-r-0 px-4 py-6 mx-4 mb-4"
    >
      <div class="flex">
        <!-- Details -->
        <div class="w-1/3 pr-2">
          <h2 class="text-lg- font-semibold mb-4">Details</h2>
          <p class="text-black text-sm leading-normal mb-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur,
            voluptatem velit suscipit modi voluptatum corporis officia esse natus nesciunt
            numquam, consectetur harum tempora minima omnis ex ab quibusdam facilis
            dolores! Minima iusto dolorem possimus quis molestiae, ipsum distinctio quasi
            reprehenderit optio, repellat velit vel vitae natus, tenetur enim commodi
            minus?
          </p>
        </div>
        <!-- Form -->
        <div class="w-2/3 pl-2">
          <div class="block md:flex mb-4">
            <!-- PID -->
            <div class="w-1/2 pr-2">
              <label class="block text-base mb-2" for="pid">PID</label>
              <input
                class="bg-gray-300 rounded p-2 w-full text-base border border-gray-500 text-gray-800 outline-none focus:border-primary"
                type="text"
                name=""
                id=""
                value="GALDZO2R4"
              />
            </div>
            <!-- CAD -->
            <div class="w-1/2 pl-2">
              <label class="block text-base mb-2" for="pid">CAD Owner Name</label>
              <input
                class="bg-gray-300 rounded p-2 w-full text-base border border-gray-500 text-gray-800 outline-none focus:border-primary"
                type="text"
                name=""
                id=""
                value="User name"
              />
            </div>
          </div>
          <!-- PROTEST ADDRESS -->
          <div class="w-full mb-4">
            <label class="block text-base mb-2" for="pid">Protest Address</label>
            <input
              class="bg-gray-300 rounded p-2 w-full text-base border border-gray-500 text-gray-800 outline-none focus:border-primary"
              type="text"
              name=""
              id=""
              value="123 Main., Galveston, TX 77555"
            />
          </div>
          <!-- CAD Mailing Address -->
          <div class="w-full mb-4">
            <label class="block text-base mb-2" for="pid">CAD Mailing Address</label>
            <input
              class="bg-gray-300 rounded p-2 w-full text-base border border-gray-500 text-gray-800 outline-none focus:border-primary"
              type="text"
              name=""
              id=""
              value="123 Main., Galveston, TX 77555"
            />
          </div>
          <!-- Other -->
          <div class="flex">
            <!-- Fee Rate -->
            <div class="w-1/3 pr-2">
              <label class="block text-base mb-2" for="pid">PID</label>
              <input
                class="bg-gray-300 rounded p-2 w-full text-base border border-gray-500 text-gray-800 outline-none focus:border-primary"
                type="text"
                name=""
                id=""
                value="40"
              />
            </div>
            <!-- Start Year -->
            <div class="w-1/3 pr-2">
              <label class="block text-base mb-2" for="pid">Start Year</label>
              <input
                class="bg-gray-300 rounded p-2 w-full text-base border border-gray-500 text-gray-800 outline-none focus:border-primary"
                type="text"
                name=""
                id=""
                value="2018"
              />
            </div>
            <!-- Agency End Date -->
            <div class="w-1/3 pr-2">
              <label class="block text-base mb-2" for="pid">Agency End Date</label>
              <input
                class="bg-gray-300 rounded p-2 w-full text-base border border-gray-500 text-gray-800 outline-none focus:border-primary"
                type="text"
                name=""
                id=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<template>
  <div class="mb-8 flex items-center justify-between">
    <h1 class="text-lg font-bold text-slate-900">Dashboard</h1>
    <button class="btn">Create link +</button>
  </div>
  <div class="mb-5">
    <div></div>
    <div class="grid grid-cols-2 lg:grid-cols-6 gap-x-5 gap-y-5">
      <div
        class="h-52 border p-4 grid grid-cols-2 gap-4 border-primary-700 shadow-primary-200 shadow-xl bg-gradient-to-br from-primary-600 to-primary-900 rounded-xl col-span-2"
      >
        <div class="flex flex-col items-start">
          <span
            class="w-10 h-10 flex mb-3 text-primary-200 items-center justify-center rounded-full bg-white/20"
          >
            <i data-feather="clock" class="text-primary-400" width="18"></i>
          </span>
          <p class="text-xl mb-1 font-bold text-white">2,000,000</p>
          <h2 class="text-primary-200 text-xs">
            Clicks made on <br />
            12 / 02 /2022
          </h2>
        </div>
        <div>
          <span
            class="w-10 h-10 flex mb-3 text-primary-200 items-center justify-center rounded-full bg-white/20"
          >
            <i
              data-feather="mouse-pointer"
              class="text-primary-400"
              width="18"
            ></i>
          </span>
          <p class="text-xl mb-1 font-bold text-white">2,000,000</p>
          <h2 class="text-primary-200 text-xs">
            Total number <br />
            of clicks made
          </h2>
        </div>
        <div class="col-span-2">
          <a
            href="#"
            class="border hover:border-primary-200 hover:text-primary-200 border-primary-500 text-xs text-primary-300 px-4 py-2 rounded-xl"
          >
            View clicks
          </a>
        </div>
      </div>
      <div
        class="h-52 border grid grid-cols-1 p-4 gap-4 bg-gradient-to-t from-primary-50 to-white border-slate-200 rounded-xl shadow-xl"
      >
        <div class="flex flex-col items-start">
          <span
            class="w-10 h-10 flex mb-3 text-primary-600 items-center justify-center rounded-full bg-primary-500/20"
          >
            <i data-feather="link" class="text-primary-400" width="18"></i>
          </span>
          <p class="text-xl mb-1 font-bold text-slate-800">2,000,000</p>
          <h2 class="text-slate-500 text-xs">
            Click links <br />
            created till date
          </h2>
        </div>
        <div>
          <a
            href="#"
            class="border hover:border-primary-800 hover:text-primary-800 border-primary-600 text-xs text-primary-500 px-4 py-2 rounded-xl"
          >
            View links
          </a>
        </div>
      </div>
      <div
        class="h-52 border grid grid-cols-1 p-4 gap-4 bg-gradient-to-t from-primary-50 to-white border-slate-200 rounded-xl shadow-xl"
      >
        <div class="flex flex-col items-start">
          <span
            class="w-10 h-10 flex mb-3 text-primary-600 items-center justify-center rounded-full bg-primary-500/20"
          >
            <i
              data-feather="mouse-pointer"
              class="text-primary-400"
              width="18"
            ></i>
          </span>
          <p class="text-xl mb-1 font-bold text-slate-800">2,000,000</p>
          <h2 class="text-slate-500 text-xs">
            Clicks left in <br />
            subscription
          </h2>
        </div>
        <div>
          <a
            href="#"
            class="border hover:border-primary-800 hover:text-primary-800 border-primary-600 text-xs text-primary-500 px-4 py-2 rounded-xl"
          >
            View subs
          </a>
        </div>
      </div>
      <div
        class="border overflow-hidden flex flex-col col-span-2 row-span-2 bg-white border-slate-200 rounded-xl shadow-xl"
      >
        <div
          class="p-4 border-b w-full flex justify-between items-center bg-gradient-to-l from-primary-50"
        >
          <div class="mr-2">
            <h4 class="text-slate-800 font-bold text-sm">Recent Links</h4>
            <p class="text-slate-500 text-xs">
              Summary of your newly created links
            </p>
          </div>
          <i data-feather="link" class="text-primary-400" width="18"></i>
        </div>
        <!-- <div>
                                <a href="#" class="border-b p-4 flex justify-between items-center hover:bg-slate-50">
                                    <dl class="w-6/12">
                                        <dt class="text-sm text-slate-700 whitespace-nowrap text-ellipsis overflow-hidden">Wazobia news</dt>
                                        <dd class="text-xs text-slate-400 whitespace-nowrap text-ellipsis overflow-hidden">
                                            http://www.wazobia-news.com
                                        </dd>
                                    </dl>
                                    <dl class="w-4/12 text-right">
                                        <dt class="text-xs text-primary-700 font-bold whitespace-nowrap text-ellipsis overflow-hidden" >
                                            7,000,000
                                        </dt>
                                        <dd class="text-xs text-primary-400 whitespace-nowrap text-ellipsis overflow-hidden">Clicks</dd>
                                    </dl>
                                </a>
                            </div> -->
        <div class="my-auto p-4 flex text-center flex-col items-center">
          <figure class="w-32 h-32 rounded-full bg-yellow-100"></figure>
          <h5 class="font-bold text-lg text-slate-700 mt-3">No links found</h5>
          <p class="text-slate-400 text-xs mt-1">
            Click the "Create link" button above <br />
            to create a new link
          </p>
        </div>
        <div class="p-4 mt-auto">
          <a
            href="#"
            class="border hover:border-primary-800 block w-full text-center hover:text-primary-800 border-primary-600 text-xs text-primary-500 px-4 py-2 rounded-xl"
          >
            View subscriptions
          </a>
        </div>
      </div>
      <div
        class="h-96 border col-span-2 lg:col-span-4 bg-white border-slate-200 rounded-xl shadow-xl overflow-hidden"
      >
        <div
          class="p-4 border-b w-full flex justify-between items-center bg-gradient-to-l from-primary-50"
        >
          <div class="w-6/12">
            <h4 class="text-slate-800 font-bold text-sm">Click statistics</h4>
            <p class="text-slate-500 text-xs">
              Statistical data of click within a selected time
            </p>
          </div>
          <div class="w-32">
            <select
              name=""
              class="w-full text-xs py-2 px-4 border-2 border-slate-300 bg-slate-200 rounded-lg appearance-none"
              id=""
            >
              <option value="weekly">Past week</option>
              <option value="year">past month</option>
              <option value="year">past year</option>
            </select>
          </div>
        </div>
      </div>
    </div>
    <footer
      class="py-8 uppercase tracking-widest text-center text-xs text-slate-400"
    >
      Custom 2022
    </footer>
  </div>
</template>
<style></style>

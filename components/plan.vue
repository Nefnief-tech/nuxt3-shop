<template>
  <h1 class="text-center font-bold text-3xl text-white pt-10">Plans</h1>
  <!--grid-->
  <div class="grid grid-cols-3 center gap-10 ml-10 mr-10">
    <!--card-1-->
    <div class="card bg-neutral-800 w-1/2 rounded-3xl mt-10">
      <!--card headdar-->
      <div class="center">
        <Icon
          name="carbon:virtual-machine"
          color="white"
          size="5rem"
          class="pt-5"
        />
      </div>
      <p class="text-white text-center p-10">
        with high performant vurtual machines we are able to offer you the best
        performance for your server. We also offer a free 7 day trial for our
        servers so you can test them out before you buy them. If you have any
        questions you can contact us at any time via our discord server or via
        email. We are looking forward to your visit.
      </p>
      <div class="footer">
        <button
          class="bg-cyan-800 hover:bg-cyan-700 text-white font-bold py-2 px-4 rounded-full"
        >
          Buy now
        </button>
      </div>
    </div>

    <!--card-2-->

    <div class="card bg-neutral-800 w-1/2 rounded-3xl mt-10">
      <!--card headdar-->
      <div class="center">
        <Icon
          name="solar:server-minimalistic-broken"
          color="white"
          size="5rem"
          class="pt-5"
        />
      </div>
      <p class="text-white text-center p-10">
        with the power of enterprise hardware and the latest technology we are
        able to offer you the best performance for your server. We also offer a
        free 7 day trial for our servers so you can test them out before you buy
        them. If you have any questions you can contact us at any time via our
        discord server or via email. We are looking forward to your visit.
      </p>
    </div>

    <!--card-3-->

    <div class="card bg-neutral-800 w-1/2 rounded-3xl mt-10">
      <!--card headdar-->
      <div class="center">
        <Icon
          name="material-symbols:shield-locked-rounded"
          color="white"
          size="5rem"
          class="pt-5"
        />
      </div>
      <p class="text-white text-center p-10">
        with our secure and encrypted network we can guarantee you the best
        protection for your server. We also offer a free 7 day trial for our
        servers so you can test them out before you buy them. If you have any
        questions you can contact us at any time via our discord server or via
        email. We are looking forward to your visit.
      </p>
    </div>
  </div>
</template>
<style>
.footer {
  justify-content: center;
  display: flex;
}
.center {
  justify-content: center;
  display: flex;
}
</style>

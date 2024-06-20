<script setup lang="ts"></script>

<template>
  <!-- <HelloWorld msg="Vite + Vue" /> -->
  <div class="container my-10 text-[#623F03]">
    <div class="grid grid-cols-[4rem_1fr_4rem] gap-4">
      <div class="flex flex-col gap-2 mt-4">
        <button
          type="button"
          class="rounded-full bg-[#623F03] px-3 py-2 text-[#EDE2C6]"
        >
          つあ
        </button>
        <button
          type="button"
          class="rounded-full bg-[#EDE2C6] px-3 py-1 text-[#623F03] font-bold border border-[#623F03] text-xl"
        >
          め
        </button>
        <button
          type="button"
          class="rounded-full bg-[#623F03] px-3 py-2 text-[#EDE2C6]"
        >
          おう
        </button>
        <button
          type="button"
          class="rounded-full bg-[#EDE2C6] text-[#623F03] font-bold flex items-center justify-center"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="5"
            stroke="currentColor"
            class="size-6"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M19.5 13.5 12 21m0 0-7.5-7.5M12 21V3"
            />
          </svg>
        </button>
      </div>
      <div class="flex flex-col gap-4 w-full items-center justify-start">
        <div class="w-full flex gap-4 items-center justify-center h-fit">
          <div class="flex-grow h-[1px] bg-[#623F03]"></div>
          <div class="font-bold text-xl italic tracking-[0.3em]">F40</div>
          <div class="flex-grow h-[1px] bg-[#623F03]"></div>
        </div>
        <div>
          <img src="/f40-car.png" alt="" />
        </div>
      </div>
      <div class="w-[4rem] relative">
        <div
          class="absolute rotate-90 w-fit left-0 top-0 translate-x-[4rem] origin-top-left p-4 flex gap-2"
        >
          <div class="flex border border-[#623F03]">
            <div class="font-bold text-lg px-2 italic">F40</div>
            <div
              class="bg-[#623F03] aspect-square w-6 flex items-center justify-center"
            >
              <div class="w-4 aspect-square">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="#EDE2C6"
                  className="size-6"
                >
                  <path
                    fillRule="evenodd"
                    d="M4.5 5.653c0-1.427 1.529-2.33 2.779-1.643l11.54 6.347c1.295.712 1.295 2.573 0 3.286L7.28 19.99c-1.25.687-2.779-.217-2.779-1.643V5.653Z"
                    clipRule="evenodd"
                  />
                </svg>
              </div>
            </div>
          </div>
          <div class="w-[30rem] text-xs font-bold">
            <span class="block"
              >0/100さす/め (62られめ): 4.1ておうそせえてとつあ</span
            >
            <span class="block">0/400ら:20.9 ておうそせえて F40</span>
          </div>
        </div>
      </div>
    </div>
    <div class="flex flex-col items-center justify-start my-3 gap-4">
      <div class="w-full h-[1px] bg-[#623F03]"></div>
      <div class="grid grid-cols-[14rem_1fr] gap-2 w-full">
        <div>
          <img src="/f40-logo.png" alt="" />
        </div>
        <div class="flex flex-col gap-1">
          <div class="grid grid-cols-[1fr_10rem] gap-2">
            <div
              class="w-full text-xs text-[0.54rem] mt-1 leading-tight font-bold tracking-"
            >
              とくおかおつつあつけか [TYPE FISO]
              けてあずけえおせきけせおつおあつ
              ぬくおおしえつけにおてたそつとてうあついなけしとかつそす 288 GTO
              ぬけとくとくおしすあせえ
              つあうおうあつにおつてけそぜてうそせとけせなけせきたつそえなうとけそせなせとけし
              1996&1994てたおうとけにおしの
              あてとくおてなううおててそつとそとくお きとそけとぬ
              えおてけきせおえとそうおしおいつあとおかおつつあつけてとくあせせけにおつてあつのあせえぬあてとくおしあてとかおつつあつけあなとそすそいけしおたおつてそせあししのあたたつそにおえ
              あととくおとけすおけとぬあてかおつつあつけ
              てかあてとおてとすそてとたそぬおつかなしあせえすそてとおねたおせてけにおうあつかそつてあしお
              とくおうあつ
            </div>
            <div
              class="font-extrabold text-4xl border border-[#623F03] tracking-tighter italic h-fit"
            >
              TYPEF120
            </div>
          </div>
          <div class="grid grid-cols-[32rem_1fr_16rem] gap-2">
            <div>
              <img src="/random-logos.png" alt="random-logos" />
            </div>
            <div
              class="w-full text-sm mt-1 font-bold tracking-tight flex flex-col"
            >
              <p>0/100さす/め (82られめ): 4.1ておうそせえてとつあ</p>
              <p>0/400ら:20.9 ておうそせえて</p>
              <p>0/1000ら:20.9 ておうそせえ</p>
              <p></p>
            </div>
            <div>
              <img src="/091-logo.png" alt="091-logo" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex flex-col gap-2 items-center justify-center mt-10 text-xl">
      <div>
        Illustration by
        <a
          href="https://www.latamarte.com/en/artists/XFVU/"
          class="font-bold opacity-75 hover:opacity-100 duration-300"
          >LATAM ARTE</a
        >
      </div>
      <div>
        Created by
        <a
          href="https://jensencher-v1.vercel.app/"
          class="font-bold opacity-75 hover:opacity-100 duration-300"
          >Jensen Cher</a
        >
      </div>
    </div>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

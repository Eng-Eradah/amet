<template>
  <div class="h-screen  text-lg leading-relaxed text-gray-800  ">
    <main class="flex flex-col justify-center items-center mx-20  my-8">
      <h1 class="font-bold text-5xl  text-center mb-10 mt-8 ">
        Tailwind CSS
      </h1>
      <section class="my-10">
        <p>
          How many lines of CSS code you’ve written in your projects? If you
          answer. A lot or even close to that. Then you are in a right place. In
          Tailwind CSS. By which you can cut down your lines of CSS by 90%. Yes,
          you read that right.
        </p>
      </section>
      <section class="my-10">
        <h2 class="font-bold my-4 ">What is Tailwind CSS?</h2>
        <p>
          Tailwind CSS is basically a utility-first CSS framework for rapidly
          building custom user interfaces.
        </p>
        <br />
        <p>
          If it was me, I would’ve named Tailwind CSS, No CSS because, that’s
          what it is. You don’t write CSS. Tailwind CSS is Utility first CSS
          framework. It’s has CSS utility classes for almost all the CSS styling
          properties. We don’t have to write CSS to style our elements. Instead
          we can use CSS utility classes generated by Tailwind CSS to style our
          elements.
        </p>
        <br> <br>
<p>
  Here is a site that presents the latest CSS statistics and the frameworks that support them during the year 2020
  </p>
           <a class="text-primary-600 " href="https://2020.stateofcss.com/en-US/technologies/css-frameworks/" > https://2020.stateofcss.com/en-US/technologies/css-frameworks/</a>
      </section>
      <section class="my-10">
        <h2 class=" font-bold my-4">Let’s look at an example</h2>
        <p>
          Below we have two similar cards. The only difference is that one’s
          with Pure CSS (Left) and other with Tailwind CSS (Right).
        </p>
        <img src="../assets/img/examples.png" alt="" class="w-300 m-auto" />
        <div class="flex justify-around">
          <div>
            <img
              class="w-1/2 m-auto block"
              src="../assets/img/purecss.png"
              alt=""
            />
          </div>
          <div>
            <img
              class="w-1/2 m-auto block"
              src="../assets/img/tailwind.png"
              alt=""
            />
          </div>
        </div>
      </section>
      <section class="my-8">
        <h2 class="font-bold my-4">How do I use Tailwind?</h2>
        <p>
          Style elements by applying pre-existing classes directly in your HTML
        </p>
      </section>
      <section class="my-10 mt-10  ">
        <h2 class="font-bold text-center text-2xl my-10  ">Padding</h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center   
          
          "
        >
          <div class="w-40 h-40 bg-primary-900  ">
            <div class="bg-primary-800 p-4 m-4 ">p-4</div>
          </div>
          <div class="w-40 h-40 bg-primary-900 ">
            <div class="bg-primary-800 pt-4 m-4">pt-4</div>
          </div>
          <div class="w-40 h-40 bg-primary-900 ">
            <div class="bg-primary-800 pl-6 m-4">pl-6</div>
          </div>
          <div class="w-40 h-40 bg-primary-900 ">
            <div class="bg-primary-800 px-4 m-4">px-4</div>
          </div>
          <div class="w-40 h-40 bg-primary-900 ">
            <div class="bg-primary-800 py-6 m-4">py-6</div>
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10  mt-32 ">Margin</h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center "
        >
          <div class="w-40 h-40 bg-primary-900 p-2  m-2 ">
            <div class="bg-primary-800  m-4">m-4</div>
          </div>
          <div class="w-40 h-40 bg-primary-900  p-2  m-2">
            <div class="bg-primary-800 mt-4">mt-4</div>
          </div>
          <div class="w-40 h-40 bg-primary-900  p-2  m-2">
            <div class="bg-primary-800  ml-6">ml-6</div>
          </div>
          <div class="w-40 h-40 bg-primary-900  p-2  m-2">
            <div class="bg-primary-800 mx-4">mx-4</div>
          </div>
          <div class="w-40 h-40 bg-primary-900  p-2  m-2">
            <div class="bg-primary-800 my-6">my-6</div>
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">
          width-height
        </h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center"
        >
          <div class="w-40 h-40 bg-primary-900 p-2  m-2 ">
            <div class="bg-primary-800 w-10 ">w-10</div>
          </div>
          <div class="w-40 h-40 bg-primary-900  p-2  m-2">
            <div class="bg-primary-800 h-20 ">h-20</div>
          </div>
          <div class="w-40 h-40 bg-primary-900  p-2  m-2">
            <div class="bg-primary-800 w-full   ">w-full</div>
          </div>
          <div class="w-40 h-40 bg-primary-900 p-2  m-2">
            <div class="bg-primary-800 w-1/2">w-1/2</div>
          </div>
          <div class="w-40 h-40 bg-primary-900  p-2  m-2">
            <div class="bg-primary-800 h-20 w-1/4">w-1/4</div>
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">Font sizes</h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center"
        >
          <div
            class="w-40 h-40 bg-primary-900 mx-3 flex justify-center items-center  text-xs p-2  m-2 "
          >
            text-xs
          </div>
          <div
            class="w-40 h-40 bg-primary-900 mx-3 flex justify-center items-center  text-sm p-2  m-2"
          >
            text-sm
          </div>
          <div
            class="w-40 h-40 bg-primary-900 mx-3 flex justify-center items-center  text-base p-2  m-2 "
          >
            text-base
          </div>
          <div
            class="w-40 h-40 bg-primary-900 mx-3 flex justify-center items-center  text-lg p-2  m-2 "
          >
            text-lg
          </div>
          <div
            class="w-40 h-40 bg-primary-900 mx-3 flex justify-center items-center  text-2xl p-2  m-2 "
          >
            text-2xl
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">Style Text</h2>
        <div
          class="grid lg:grid-cols-3 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center"
        >
          <div class="w-40 h-40 bg-primary-900 mx-3  text-left p-2  m-2">
            text-left
          </div>
          <div class="w-40 h-40 bg-primary-900 mx-3  text-right p-2  m-2">
            text-right
          </div>
          <div class="w-40 h-40 bg-primary-900 mx-3  text-center p-2  m-2">
            text-center
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">Text colors</h2>
        <div
          class="grid lg:grid-cols-3 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center"
        >
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center  p-2  m-2 "
          >
            text-white
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center text-gray-200 p-2  m-2"
          >
            text-gray-200
          </div>
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center text-red-600 p-2  m-2"
          >
            text-center
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">
          Background colors
        </h2>
        <div
          class="grid lg:grid-cols-3 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center"
        >
          <div
            class="w-40 h-40 bg-blue-100 flex justify-center items-center text-black p-2  m-2  "
          >
            bg-blue-100
          </div>
          <div
            class="w-40 h-40 bg-blue-500  flex justify-center items-center text-white p-2  m-2"
          >
            bg-blue-500
          </div>
          <div
            class="w-40 h-40 bg-blue-900 flex justify-center items-center text-white p-2  m-2"
          >
            bg-blue-900
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">Rounded</h2>
        <div
          class="grid lg:grid-cols-3 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center"
        >
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center rounded-lg  p-2  m-2"
          >
            rounded-lg
          </div>
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center rounded-full p-2  m-2"
          >
            rounded-full
          </div>
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center rounded-tl-full  p-2  m-2"
          >
            rounded-tl-full
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">Style Text</h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center"
        >
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center italic p-2  m-2 "
          >
            italic
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center underline p-2  m-2"
          >
            underline
          </div>
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center line-through p-2  m-2  "
          >
            line-through
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center uppercase p-2  m-2 "
          >
            uppercase
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center capitalize p-2  m-2 "
          >
            capitalize
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10  mt-32">Font-weight</h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center "
        >
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center font-thin p-2  m-2  "
          >
            font-thin(200)
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center font-medium p-2  m-2 "
          >
            font-medium(500)
          </div>
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center font-semibold p-2  m-2 "
          >
            font-semibold(600)
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center font-bold p-2  m-2 "
          >
            font-bold(700)
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center font-black p-2  m-2 "
          >
            font-black(900)
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10 mt-32 ">
          Letter Spacing
        </h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center "
        >
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center  p-2 m-2 tracking-tighter "
          >
            tracking-tight(-0.05em) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center p-2 m-2 tracking-normal "
          >
            tracking-normal(0em) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center p-2 m-2 tracking-wide "
          >
            tracking-wide(0.025em) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center p-2 m-2 tracking-wider "
          >
            tracking-wider(0.05em) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center p-2 m-2 tracking-widest "
          >
            tracking-black(0.1em) Lorem ipsum dolor sit amet.
          </div>
        </div>

        <h2 class="font-bold text-center text-2xl my-10  mt-32">Line Height</h2>
        <div
          class="grid lg:grid-cols-5 md:grid-cols-3 sm:grid-cols-2 text-white gap-4 justify-items-center items-center "
        >
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center  p-2 leading-tight m-2"
          >
            tracking-tight(1.25) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center p-2  m-2 leading-snug "
          >
            leading-snug(1.375) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900 flex justify-center items-center p-2  m-2 leading-normal "
          >
            leading-normal(1.5) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center p-2  m-2 leading-relaxed "
          >
            leading-relaxed(1.625) Lorem ipsum dolor sit amet.
          </div>
          <div
            class="w-40 h-40 bg-primary-900  flex justify-center items-center p-2  m-2 leading-loose "
          >
            leading-loose(2) Lorem ipsum dolor sit amet.
          </div>
        </div>
      </section>
    </main>
    <footer
      class=" text-center py-3 font-medium text-sm w-full h-10 bg-primary-900"
    >
      All rights recieved to rowad
    </footer>
  </div>
</template>

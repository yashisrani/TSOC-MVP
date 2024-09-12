<script lang="ts">
    import { createLabel, melt } from '@melt-ui/svelte';
  
    const {
      elements: { root },
    } = createLabel();
  </script>
 
 <div class="flex justify-center text-center mt-20 items-start w-full gap-2">
    <div >
        <svg  id="logo-15" width="42" height="42" viewBox="0 0 49 48" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M24.5 12.75C24.5 18.9632 19.4632 24 13.25 24H2V12.75C2 6.53679 7.03679 1.5 13.25 1.5C19.4632 1.5 24.5 6.53679 24.5 12.75Z" class="ccustom" fill="#17CF97"></path> <path d="M24.5 35.25C24.5 29.0368 29.5368 24 35.75 24H47V35.25C47 41.4632 41.9632 46.5 35.75 46.5C29.5368 46.5 24.5 41.4632 24.5 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M2 35.25C2 41.4632 7.03679 46.5 13.25 46.5H24.5V35.25C24.5 29.0368 19.4632 24 13.25 24C7.03679 24 2 29.0368 2 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M47 12.75C47 6.53679 41.9632 1.5 35.75 1.5H24.5V12.75C24.5 18.9632 29.5368 24 35.75 24C41.9632 24 47 18.9632 47 12.75Z" class="ccustom" fill="#17CF97"></path> </svg>
    </div>
    <p class="text-center text-3xl">We<span class="font-bold text-3xl">Fund</span></p>
</div>

<div class="flex justify-center items-center gap-10 mt-14">
  <h1 class="text-2xl font-semibold">Welcome to WeFund !!</h1>
</div>
<div class="flex justify-center items-center gap-10 mt-2 opacity-40">
 <p>Please login to your account to continue.</p>
</div>

 <div class="flex justify-center items-center pt-20 gap-14">
    <form>
        <div class="flex flex-col items-start justify-center">
          <label
            use:melt={$root}
            for="email"
            class="mb-0.5 font-medium text-magnum-900"
            data-melt-part="root"
          >
            <span>Name</span>
          </label>
          <input
            type="text"
            id="Name"
            class="h-10 w-[240px] rounded-md bg-white px-3 py-2 text-magnum-700 border"
            placeholder="Full Name"
          />
        </div>
      </form>
      <form>
        <div class="flex flex-col items-start justify-center">
          <label
            use:melt={$root}
            for="email"
            class="mb-0.5 font-medium text-magnum-900"
            data-melt-part="root"
          >
            <span>Phone no.</span>
          </label>
          <input
            type="tel"
            id="phone"
            class="h-10 w-[240px] rounded-md bg-white px-3 py-2 text-magnum-700 border"
            placeholder="Enter your phone number"
          />
        </div>
      </form>
      
 </div>

 <div class="flex justify-center items-center gap-10 mt-28">
  <a href="/otp">
    <button type="submit" class="bg-magnum-900 text-white font-medium py-3 px-9 rounded-full bg-[#17CF97]">
      Submit
    </button>
  </a>
 </div>

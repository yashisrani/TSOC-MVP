<script lang="ts">
    import { PinInput, Toggle } from "bits-ui";
   
   
    let value: string[] | undefined = [];
   
    let unlocked = true;
    let pinInputType: "text" | "password" = "password";
    $: pinInputType = unlocked ? "text" : "password";
  </script>

<div class="flex justify-center text-center mt-20 items-start w-full gap-2">
    <div >
        <svg  id="logo-15" width="40" height="38" viewBox="0 0 49 48" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M24.5 12.75C24.5 18.9632 19.4632 24 13.25 24H2V12.75C2 6.53679 7.03679 1.5 13.25 1.5C19.4632 1.5 24.5 6.53679 24.5 12.75Z" class="ccustom" fill="#17CF97"></path> <path d="M24.5 35.25C24.5 29.0368 29.5368 24 35.75 24H47V35.25C47 41.4632 41.9632 46.5 35.75 46.5C29.5368 46.5 24.5 41.4632 24.5 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M2 35.25C2 41.4632 7.03679 46.5 13.25 46.5H24.5V35.25C24.5 29.0368 19.4632 24 13.25 24C7.03679 24 2 29.0368 2 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M47 12.75C47 6.53679 41.9632 1.5 35.75 1.5H24.5V12.75C24.5 18.9632 29.5368 24 35.75 24C41.9632 24 47 18.9632 47 12.75Z" class="ccustom" fill="#17CF97"></path> </svg>
    </div>
    <p class="text-center text-2xl">We<span class="font-bold text-2xl">Fund</span></p>
</div>

<div class="flex justify-center items-center gap-10 mt-14">
    <h1 class="text-2xl font-semibold">Enter OTP Code</h1>
  </div>
  <div class="flex justify-center items-center gap-10 mt-2 opacity-40">
    <p>Please enter the code that was sent to yout number to verify your account.</p>
   </div>

   <div class="flex justify-center items-center mt-10">
    <PinInput.Root
  bind:value
  class="flex items-center gap-2"
  type={pinInputType}
  placeholder="0"
>
  <PinInput.Input
    class="flex h-input w-10 select-none rounded-input border border-foreground bg-background px-2 py-3 text-center font-alt text-[17px] tracking-[0.01em] text-foreground placeholder-shown:border-border-input focus-within:border-border-input-hover focus-within:shadow-date-field-focus hover:border-border-input-hover"
  />
  <PinInput.Input
    class="flex h-input w-10 select-none rounded-input border border-foreground bg-background px-2 py-3 text-center font-alt text-[17px] tracking-[0.01em] text-foreground placeholder-shown:border-border-input focus-within:border-border-input-hover focus-within:shadow-date-field-focus hover:border-border-input-hover"
  />
  <PinInput.Input
    class="flex h-input w-10 select-none rounded-input border border-foreground bg-background px-2 py-3 text-center font-alt text-[17px] tracking-[0.01em] text-foreground placeholder-shown:border-border-input focus-within:border-border-input-hover focus-within:shadow-date-field-focus hover:border-border-input-hover"
  />
  <PinInput.Input
    class="flex h-input w-10 select-none rounded-input border border-foreground bg-background px-2 py-3 text-center font-alt text-[17px] tracking-[0.01em] text-foreground placeholder-shown:border-border-input focus-within:border-border-input-hover focus-within:shadow-date-field-focus hover:border-border-input-hover"
  />
  <PinInput.HiddenInput />
  
</PinInput.Root>
   </div>

   <div class="flex justify-center items-center gap-10 mt-6 opacity-60">
    <p>Didn't receive it? Retry in 00:29</p>
   </div>

   <div class="flex justify-center items-center gap-10 mt-24">
    <a href="/otp_verified">
      <button type="submit" class="bg-magnum-900 text-white font-medium py-3 px-9 rounded-full bg-[#17CF97]">
        Confirm
      </button>
    </a>
 </div>
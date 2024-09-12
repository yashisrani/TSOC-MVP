<script >
    let selectedOptions = {
      option1: false,
      option2: false,
      option3: false,
      option4: false,
      option5: false,
      option6: false,
      option7: false,
      option8: false,
      option9: false,
      option10: false,
   
    };
  </script>

<div class="flex justify-center text-center mt-8 items-start w-full gap-2">
    <div >
        <svg  id="logo-15" width="40" height="38" viewBox="0 0 49 48" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M24.5 12.75C24.5 18.9632 19.4632 24 13.25 24H2V12.75C2 6.53679 7.03679 1.5 13.25 1.5C19.4632 1.5 24.5 6.53679 24.5 12.75Z" class="ccustom" fill="#17CF97"></path> <path d="M24.5 35.25C24.5 29.0368 29.5368 24 35.75 24H47V35.25C47 41.4632 41.9632 46.5 35.75 46.5C29.5368 46.5 24.5 41.4632 24.5 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M2 35.25C2 41.4632 7.03679 46.5 13.25 46.5H24.5V35.25C24.5 29.0368 19.4632 24 13.25 24C7.03679 24 2 29.0368 2 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M47 12.75C47 6.53679 41.9632 1.5 35.75 1.5H24.5V12.75C24.5 18.9632 29.5368 24 35.75 24C41.9632 24 47 18.9632 47 12.75Z" class="ccustom" fill="#17CF97"></path> </svg>
    </div>
    <p class="text-center text-2xl">We<span class="font-bold text-2xl">Fund</span></p>
</div>

<div class="flex justify-center items-start w-full mt-10">
    <h2 class="text-2xl font-semibold mb-4 text-gray-800">Select Contract</h2>
</div>
  
 
  <div class="flex justify-center items-center mt-7 "> 
    <div class="p-6 bg-white rounded-lg shadow-md max-w-md mx-auto">
       
      
        <div class="flex items-center mb-3">
          <input type="checkbox" id="option1" bind:checked={selectedOptions.option1} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
          <label for="option1" class="ml-2 text-sm text-gray-900">Housing Association</label>
        </div>
      
        <div class="flex items-center mb-3">
          <input type="checkbox" id="option2" bind:checked={selectedOptions.option2} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
          <label for="option2" class="ml-2 text-sm text-gray-900">Event Expenses</label>
        </div>
      
        <div class="flex items-center mb-3">
          <input type="checkbox" id="option3" bind:checked={selectedOptions.option3} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
          <label for="option3" class="ml-2 text-sm text-gray-900">Office Space Rent Sharing</label>
        </div>

        <div class="flex items-center mb-3">
            <input type="checkbox" id="option3" bind:checked={selectedOptions.option4} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
            <label for="option3" class="ml-2 text-sm text-gray-900">Travel Expenses Split</label>
          </div>

          <div class="flex items-center mb-3">
            <input type="checkbox" id="option3" bind:checked={selectedOptions.option5} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
            <label for="option3" class="ml-2 text-sm text-gray-900">Project Collaboration Funds</label>
          </div>

          <div class="flex items-center mb-3">
            <input type="checkbox" id="option3" bind:checked={selectedOptions.option6} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
            <label for="option3" class="ml-2 text-sm text-gray-900">Shared vacation budget</label>
          </div>

          <div class="flex items-center mb-3">
            <input type="checkbox" id="option3" bind:checked={selectedOptions.option7} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
            <label for="option3" class="ml-2 text-sm text-gray-900">Group Budget</label>
          </div>

          <div class="flex items-center mb-3">
            <input type="checkbox" id="option3" bind:checked={selectedOptions.option8} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
            <label for="option3" class="ml-2 text-sm text-gray-900">Community Events</label>
          </div>

          <div class="flex items-center mb-3">
            <input type="checkbox" id="option3" bind:checked={selectedOptions.option9} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
            <label for="option3" class="ml-2 text-sm text-gray-900">Joint Ventures</label>
          </div>

          <div class="flex items-center mb-3">
            <input type="checkbox" id="option3" bind:checked={selectedOptions.option10} class="h-4 w-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500">
            <label for="option3" class="ml-2 text-sm text-gray-900">Charity Donation</label>
          </div>
      
        
      </div>
  </div>
  <div class="flex justify-center items-center gap-10 mt-7 mb-3">
    <a href="/contractinfo">
      <button type="submit" class="bg-magnum-900 text-white font-medium py-3 px-9 rounded-full bg-[#17CF97]">
        Confirm
      </button>
    </a>
    </div>
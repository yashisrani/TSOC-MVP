<div class="flex justify-center text-center mt-14 items-start w-full gap-2">
    <div >
        <svg  id="logo-15" width="40" height="38" viewBox="0 0 49 48" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M24.5 12.75C24.5 18.9632 19.4632 24 13.25 24H2V12.75C2 6.53679 7.03679 1.5 13.25 1.5C19.4632 1.5 24.5 6.53679 24.5 12.75Z" class="ccustom" fill="#17CF97"></path> <path d="M24.5 35.25C24.5 29.0368 29.5368 24 35.75 24H47V35.25C47 41.4632 41.9632 46.5 35.75 46.5C29.5368 46.5 24.5 41.4632 24.5 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M2 35.25C2 41.4632 7.03679 46.5 13.25 46.5H24.5V35.25C24.5 29.0368 19.4632 24 13.25 24C7.03679 24 2 29.0368 2 35.25Z" class="ccustom" fill="#17CF97"></path> <path d="M47 12.75C47 6.53679 41.9632 1.5 35.75 1.5H24.5V12.75C24.5 18.9632 29.5368 24 35.75 24C41.9632 24 47 18.9632 47 12.75Z" class="ccustom" fill="#17CF97"></path> </svg>
    </div>
    <p class="text-center text-2xl">We<span class="font-bold text-2xl">Fund</span></p>
</div>

<div class="flex justify-center items-start w-full mt-10">
    <h2 class="text-2xl font-semibold mb-4 text-gray-800">Housing Association Contract</h2>
</div>


   
<script>
  let selectedOption = '';  // Tracks the selected option
  let selectedOption1 = '';
  let inputValue = '';
  let selectedDate = '';
  let selectedDate1 = '';
</script>

<div class="max-w-md mx-auto p-4">
  <label for="options" class="block text-sm font-medium text-gray-700 mb-2">Type of Splits:</label>
  <select id="options" bind:value={selectedOption} class="block w-full px-3 py-2 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
    <option value="" disabled>Select an option</option>
    <option value="option1">Percentage Based</option>
    <option value="option2">Option 2</option>
    <option value="option3">Option 3</option>
  </select>

  
</div>

<div class="max-w-md mx-auto p-4">
  <label for="options" class="block text-sm font-medium text-gray-700 mb-2">Payment Frequency:</label>
  <select id="options" bind:value={selectedOption1} class="block w-full px-3 py-2 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
    <option value="" disabled>Select an option</option>
    <option value="option1">Daily</option>
    <option value="option2">Monthly</option>
    <option value="option3">Yearly</option>
  </select>

  
</div>


<div class="max-w-md mx-auto p-4">
  <label for="input" class="block text-sm font-medium text-gray-700 mb-2">Contribution Amount:</label>
  <input 
    type="text" 
    id="input" 
    bind:value={inputValue} 
    class="block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" 
    placeholder="Enter Amount:"
  >
  
  
</div>

<div class="max-w-md mx-auto p-4">
  <label for="date" class="block text-sm font-medium text-gray-700 mb-2">Start date:</label>
  <input 
    type="date" 
    id="date" 
    bind:value={selectedDate} 
    class="block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm"
  >

  
</div>
<div class="max-w-md mx-auto p-4">
  <label for="date" class="block text-sm font-medium text-gray-700 mb-2">End date:</label>
  <input 
    type="date" 
    id="date" 
    bind:value={selectedDate1} 
    class="block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm"
  >

 
</div>
<div class="flex justify-center items-center gap-10 mt-7">
  <button type="submit" class="bg-magnum-900 text-white font-medium py-3 px-9 rounded-full bg-[#17CF97]">
    Confirm
  </button>
  </div>
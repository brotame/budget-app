<script>
  //Exports
  export let category;
</script>

<div class="transaction_badge expense w-embed">
  {#if category === 'Rent'}
    <svg
      viewBox="0 0 38 38"
      fill="none"
      stroke="currentColor"
      xmlns="http://www.w3.org/2000/svg">
      <path
        d="M32 19V36H6V19"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M23 23H15V36H23V23Z"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M34 20L19 8L4 20L1 16L19 2L37 16L34 20Z"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M11 8V5H6V12"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
    </svg>
  {:else if category === 'Leisure'}
    <svg
      viewBox="0 0 44 44"
      fill="none"
      stroke="currentColor"
      xmlns="http://www.w3.org/2000/svg">
      <path
        d="M23.1001 36.5C31.3844 36.5 38.1001 29.7843 38.1001 21.5C38.1001
        13.2157 31.3844 6.5 23.1001 6.5C14.8158 6.5 8.1001 13.2157 8.1001
        21.5C8.1001 29.7843 14.8158 36.5 23.1001 36.5Z"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M28.7771 27.1069C34.5959 21.2881 36.7803 14.0384 33.6561
        10.9143C30.5319 7.7901 23.2823 9.97449 17.4635 15.7933C11.6448 21.612
        9.46037 28.8617 12.5845 31.9858C15.7087 35.11 22.9584 32.9256 28.7771
        27.1069Z"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M7.8999 19.9C11.1999 20.5 15.1999 22.7 18.6999 26.2C21.9999 29.5
        24.1999 33.3 24.8999 36.6"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M37.6 23.8C34.4 23.1 30.6 20.9 27.3 17.6C23.8 14.1 21.6 10.1 21
        6.79999"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M33.4998 11.4L12.2998 32.5"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M33.4002 32.3L12.2002 11.1"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M16.2 2C12.9 3 10 5.2 8.1 7.1C6.4 8.8 5 10.8 4 12.9L1 11.4"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M37.7002 7.70001C37.9002 7.90001 38.1002 8.20001 38.4002 8.50001"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M40.0001 10.8C44.8001 18.7 43.8001 29.1 37.0001 36C29.0001 44 16.1001
        44 8.10015 36C3.80015 31.7 1.80015 25.9 2.10015 20.2"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-dasharray="1.96 1.96" />
      <path
        d="M2.30029 18.7C2.30029 18.4 2.40029 18 2.50029 17.7"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M3.3999 6.7L9.1999 6"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
    </svg>
  {:else}
    <svg
      viewbox="0 0 40 40"
      fill="none"
      stroke="currentColor"
      xmlns="http://www.w3.org/2000/svg">
      <path
        d="M29.937 10.0761H32.5302L33.9265 39H6L7.29659 10.0761H9.9895"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M12.9816 10.0761H26.9449"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M6.99738 31.021H32.9291"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M12.9816 16.0604V7.78215C12.9816 4.09186 16.0735 1 19.8635
        1H19.9633C23.7533 1 26.8451 3.99213 26.8451 7.78215V15.9606"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M10.9869 16.0604H14.9764"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
      <path
        d="M24.9501 16.0604H28.9396"
        stroke-width="1.5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round" />
    </svg>
  {/if}
</div>

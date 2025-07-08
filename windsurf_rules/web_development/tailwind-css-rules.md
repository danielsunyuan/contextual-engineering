# Tailwind CSS Rules for Windsurf

- Use responsive prefixes for mobile-first design:
  ```html
  <div class="w-full md:w-1/2 lg:w-1/3">
    <!-- Full width on mobile, half on medium, one-third on large screens -->
  </div>
  ```
- Use state variants for interactive elements:
  ```html
  <button class="bg-blue-500 hover:bg-blue-600 active:bg-blue-700">
    <!-- Button color changes on hover and click -->
  </button>
  ```

Source: Adapted from Playbooks Windsurf Rules at https://playbooks.com/windsurf-rules

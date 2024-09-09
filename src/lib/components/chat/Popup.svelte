<script>
    export let message = '';
  </script>
  
  <div class="popup">
    {message}
  </div>
  
  <style>
    .popup {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: rgba(100, 68, 105, 0.8); /* Opaque purple background */
      padding: 20px;
      border-radius: 10px;
      color: white; /* Text color */
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
      z-index: 1000;
      text-align: center;
    }
  </style>
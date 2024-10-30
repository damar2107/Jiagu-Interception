<h2>How to Use</h2>

<ol>
  <li>Build the source code (make sure you have installed NDK &amp; CMake)</li>
  <li>Go to <code>output/build</code> and install the application or if you use an emulator, you have to set the flag and add the x86 architecture.</li>
  <li>Install the application</li>
  <li>Login with this user's account:
    <ul>
      <li>Email: <code>admin-javaloader@enigma.com</code></li>
      <li>Password: <code>123456</code></li>
    </ul>
  </li>
  <li>All electricity data will be shown in the dashboard menu. If the data does not appear, it means that the hardware is not plugged into the electricity or there is an internet problem where the hardware is running.</li>
</ol>

<h2>Application Overview</h2>

<p>Our application is an electricity monitoring tool capable of tracking both household AC electricity and DC current, making it ideal for solar panel applications. By using sensors such as the PZEM004t, DHT, and ESP32, we can capture real-time electric current data, which is then sent to the server and displayed in our application.</p>

<p>In developing our application, we use Docker, WebSocket, Kafka, and Firebase, each playing a distinct role within the system.</p>

<p>Additionally, we have implemented an advanced anti-tampering feature to detect and prevent unauthorized interference. This feature alerts the system if any attempt is made to alter or manipulate the monitoring hardware or software, ensuring data integrity and reliable performance.</p>

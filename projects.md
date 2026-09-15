---
layout: default
---

# Projects

<div class="tab-buttons">
  <button class="tab-btn active" onclick="showTab('softdev_tab')">Software Development</button>
  <button class="tab-btn" onclick="showTab('data_tab')">Database Administration / Data Engineering</button>
  <button class="tab-btn" onclick="showTab('others_tab')">Others</button>
</div>

<div id="softdev_tab" class="tab-content active">
    <h3>Aswang Busters</h3>
    <p>Awang Busters was a small game project created to participate in Hackathon "Game-On: Game Developer's Gauntlet". It is also my first introduction into Python.
    The premise of the game is simply to shoot as many Aswangs (A Filipino Ghost) in the given time, instead of a normal mouse and keyboard. The game uses a Nintendo Switch's Joycon for controls, leveraging and taking advantage of its built-in gyroscope module for aiming.
    </p>
    <h4>Built With:</h4>
    <ul>
        <li>Python</li>
        <li>Tkinter for GUI</li>
        <li>joycon-python Library for Nintendo Switch Joy-Con Driver</li>
    </ul>
    <h4>screenshot(s)</h4>
    <img src="assets/images/Aswang Busters.png" alt="Aswang Busters" width="637" height="358" style="max-width: 100%; height: auto;" />
    <img src="assets/images/FB_IMG_1789384698425.jpg" alt="FB_IMG_1789384698425" width="350" height="350" style="max-width: 100%; height: auto;" />

</div>

<div id="data_tab" class="tab-content">
  <ul>
    <li>Project C — short description</li>
    <li>Project D — short description</li>
  </ul>
</div>

<div id="others_tab" class="tab-content">
  <ul>
    <li>Project E — short description</li>
    <li>Project F — short description</li>
  </ul>
</div>

<script>
function showTab(id) {
  document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
  document.querySelectorAll('.tab-btn').forEach(el => el.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  event.target.classList.add('active');
}
</script>
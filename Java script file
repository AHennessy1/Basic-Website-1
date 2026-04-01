/* ============================= */
/* BOX BREATHING (4-4-4-4) */
/* ============================= */

const breathingCircle = document.querySelector(".breathing-circle-main");
const breathText = document.getElementById("breath-text");

function breathingCycle() {

    // INHALE (0–4s)
    breathText.textContent = "Breathe In...";
    breathingCircle.classList.add("expand");

    // HOLD (4–8s)
    setTimeout(() => {
        breathText.textContent = "Hold...";
    }, 4000);

    // EXHALE (8–12s)
    setTimeout(() => {
        breathText.textContent = "Breathe Out...";
        breathingCircle.classList.remove("expand");
    }, 8000);

    // HOLD (12–16s)
    setTimeout(() => {
        breathText.textContent = "Hold...";
    }, 12000);
}

breathingCycle();
setInterval(breathingCycle, 16000);

/* ============================= */
/* Candle Game
/* ============================= */
const lightBtn = document.getElementById('light-btn');
const blowBtn = document.getElementById('blow-btn');
const candleImage = document.querySelector('.candle-image');
const candleGlow = document.querySelector('.candle-glow');

lightBtn.addEventListener('click', () => {
  candleImage.src = 'Images/candlelit.png';  // switch to lit image
  candleGlow.classList.add('lit');           // show flickering glow
});

blowBtn.addEventListener('click', () => {
  candleImage.src = 'Images/candleunlit.png'; // switch to unlit image
  candleGlow.classList.remove('lit');        // hide glow
});

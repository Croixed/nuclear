<div class="info">
  <div class="top-slide">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M1200 120L0 16.48 0 0 1200 0 1200 120z" class="shape-fill"></path>
    </svg>
</div>
  <p>...</p>
  <div class="slide">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M1200 120L0 16.48 0 0 1200 0 1200 120z" class="shape-fill"></path>
    </svg>
  </div>
</div>

<style>
.info {
  background-color: #174;
  height: 300px;
  position: relative;

  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 18vw 100px 18vw;
  
}

  /* ehhh */
  .slide {
    position: absolute;
    bottom: -90px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    z-index: 2;
} 

.slide svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 90px;
  }

.slide .shape-fill {
    fill: #117744;
  }

  .top-slide {
    position: absolute;
    top: -90px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    transform: rotate(180deg);
}

.top-slide svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 90px;
    transform: rotateY(180deg);
}

.top-slide .shape-fill {
    fill: #117744;
}
</style>

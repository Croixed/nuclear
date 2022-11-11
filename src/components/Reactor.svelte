<div class="reactor">
  <p>reactor</p>
  <div class="slide">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M1200 120L0 16.48 0 0 1200 0 1200 120z" class="shape-fill"></path>
    </svg>
</div>
</div>



<style>


  .reactor {
    background-color: #163;

    height: 400px;
    position: relative;

    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 100px 18vw;
  }

  .slide {
    position: absolute;
    bottom: -90px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    z-index: 3;
}

.slide svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 90px;
    transform: rotateY(180deg);
}

.slide .shape-fill {
    fill: #116633;
}
</style>
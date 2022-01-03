<template>
  <div class="team-wrap">
    <section class="our-team" id="Team">
      <div class="team-typo">
        <h1 class="text-white text-4xl">Meet Our Team</h1>
        <p class="text-white text-2xl">
          Each member of our team is truly passionate and dedicated to the
          Wierd Bear which will ensure success
        </p>
      </div>
      <div class="team-dp">
        <div class="dp">
          <img
            class="team-img w-72"
            src="../assets/TeamPictures/RamzanAli.png"
            alt="Ramzan Ali M"
          />
          <h1>Ramzan Ali M</h1>
          <p>Founder & CEO</p>

        </div>
        <div class="dp">
          <img
            class="team-img w-72"
            src="../assets/TeamPictures/Sara.png"
            alt="Sara Fathima"
          />
          <h1>Sara Fathima</h1>
          <p>Co-founder</p>
        </div>
        <div class="dp">
          <img
            class="team-img w-72"
            src="../assets/TeamPictures/Shahul.png"
            alt="Shahul Munavar"
          />
          <h1>Shahul Munavar</h1>
          <p>MD & Content Creator</p>

        </div>
        <div class="dp">
          <img
            class="team-img w-72"
            src="../assets/TeamPictures/Vishwa.png"
            alt="Vishwa"
          />
          <h1>Vishwa</h1>
          <p>Head Designer</p>


        </div>

        <div class="dp">
          <img
            class="team-img w-72"
            src="../assets/TeamPictures/Alimoan.png"
            alt="Ramzan Ali M"
          />
          <h1>Ramzan Ali M</h1>
          <p>Designer </p>


        </div>
      </div>
    </section>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.team-wrap {
  margin-top: 6.5rem;
  margin-bottom: 6.5rem;
}

.dp {
  border: 1px solid rgba(128, 128, 128, 0.452);
  padding: 10px;
  margin-top: 10px;
  margin-bottom: 10px;
  border-radius: 7px;
  box-shadow: 1px 0px 5px 1px rgba(214, 214, 214, 0.164);
  transition: all 0.24s;
}

.dp:hover {
  transform: scale(1.02);
  box-shadow: 1px 2px 10px 1px rgba(240, 255, 213, 0.315);
}

.our-team {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
}

.team-dp {
  display: flex;

  flex-wrap: wrap;

  justify-content: center;
  h1 {
    margin-top: 0.6rem;
    color: white;
    font-size: 1.2rem;
  }
  h1::after {
    content: "";
    display: block;
    width: 150px;
    height: 10px;
    margin-top: 1rem;
    margin-bottom: 0.8rem;
    background-color: #ec4899;
  }

  p {
    // color: #08dfc2;
    color: #6EE7B7;
    font-size: .9rem;
  }

  .dp {
    max-width: max-content;
    margin-left: 1.2rem;
    flex: 0 0 15.333333%;

    img {
      border-radius: 10px;
      transition: all 0.24s;
      box-shadow: 1px 2px 10px 5px rgba(161, 161, 161, 0.158);
    }
    img:hover {
      transform: rotate(3deg);
    }
  }
}

.team-typo {
  text-align: center;
  max-width: 75rem;

  h1 {
    margin-bottom: 3.8rem;
    font-weight: bold;
    color: #ec4899;
  }

  p {
    margin-bottom: 3.5rem;
  }
}

.contact-team {
  margin-bottom: 20px;
}
@media (max-width: 900px) {
  .dp {
    margin-left: 0 !important;
  }
  .team-dp {
    flex-direction: column;
  }
  .team-wrap {
    margin-top: 4.5rem;
    margin-bottom: 4.5rem;
  }
  .team-typo {
    max-width: 300px;
  }
}
</style>

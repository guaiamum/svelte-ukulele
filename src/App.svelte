<script>
  import Audio from "./components/Audio.svelte";

  let audio;

  function startPlaying() {
    setTimeout(() => {
      audio.play();
    }, 500);
  }
</script>

<main on:scroll={startPlaying}>
  <Audio bind:audioRef={audio} />
  <h1>Aigdsahb 🍄💙</h1>
  <p>
    Nulla deserunt id incididunt occaecat duis do minim nostrud velit do nisi. Cupidatat eiusmod est proident laborum aliquip voluptate nulla sit. Excepteur tempor anim qui est nisi officia elit proident consectetur exercitation laborum laboris. Officia cupidatat et sunt culpa ipsum mollit dolor eu ipsum est aute incididunt.
    Nulla deserunt id incididunt occaecat duis do minim nostrud velit do nisi. Cupidatat eiusmod est proident laborum aliquip voluptate nulla sit. Excepteur tempor anim qui est nisi officia elit proident consectetur exercitation laborum laboris. Officia cupidatat et sunt culpa ipsum mollit dolor eu ipsum est aute incididunt.
  </p>
  <h2>Pt. 2</h2>
  <p>
    Sunt et amet labore dolor excepteur velit exercitation consequat dolor. Cillum duis tempor pariatur dolore adipisicing deserunt do culpa mollit cupidatat mollit tempor excepteur. Aute pariatur aliqua cillum amet Lorem commodo nulla reprehenderit aliquip nisi veniam enim nostrud dolore. Sint sint sit velit occaecat cillum cillum ad. Aute exercitation labore nostrud duis consequat do esse anim duis labore id reprehenderit ad. Lorem in do commodo ut.🤷‍♂️😄
  </p>
</main>

<style>
  main {
    font-family: "Didot Light";
    font-size: 2em;
  }

  @media only screen and (max-width: 600px) {
    main {
      font-family: "Didot Medium";
    }
  }

  h1,
  h2 {
    font-family: "Didot";
    font-style: italic;
    font-weight: bold;
  }

  p {
    font-size: 1.5rem;
    text-align: justify;
    margin: 0 1rem;
  }
</style>

<script lang="ts">
  const hello: string = 'world';
  import Image from 'svimg'
</script>

<style lang="scss">
  section{
    @apply bg-red-50 p-3;
    p{
      @apply text-[brown] bg-blue-50 p-2 rounded;
    }
  }
</style>

<section>
  <p>hey yay</p>
</section>

<Image src="girls.jpg" />

<section>
  <p>yay hey {hello}</p>
</section>
<template>
  <TheBanner text="This is the banner text" />
  <main class="max-w-7xl my-0 mx-auto">
    <img class="w-full" src="/assets/desert.png" />
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus a
      dapibus risus, sed venenatis nibh. Cras malesuada, justo et consectetur
      suscipit, purus ex feugiat libero, non elementum eros nisl sed libero.
      Vivamus sit amet dui convallis, mollis orci nec, viverra dui. Proin neque
      purus, fringilla ut lacus at, commodo cursus urna. Vivamus tempor, mauris
      vitae rutrum dictum, velit mi feugiat arcu, lacinia placerat est mauris
      nec augue. Nulla quis vulputate diam, ut tempus nunc. Donec interdum enim
      lorem, quis placerat lacus imperdiet vitae. Suspendisse metus leo, dapibus
      et massa vel, posuere venenatis libero. Interdum et malesuada fames ac
      ante ipsum primis in faucibus. Nunc cursus egestas dolor at bibendum.
    </p>
    <p>
      Vivamus sit amet consequat libero. Donec in tincidunt ante, quis ultricies
      est. Class aptent taciti sociosqu ad litora torquent per conubia nostra,
      per inceptos himenaeos. Ut rhoncus mollis mauris a mollis. Aenean placerat
      sapien id lectus consectetur tempor. In hac habitasse platea dictumst.
      Nulla elit metus, feugiat sit amet varius sit amet, porttitor eu nulla.
      Cras ornare fringilla nunc quis varius. Donec tellus lectus, tincidunt ut
      laoreet et, venenatis nec neque. Suspendisse id libero magna. Mauris nisl
      dui, porta eget posuere in, scelerisque nec urna.
    </p>
    <p>
      Cras turpis ante, luctus non eleifend eu, aliquam eleifend ligula. Ut
      pretium tincidunt tortor, vel consectetur metus pellentesque eu. Nunc non
      magna turpis. Maecenas pretium risus nec posuere aliquet. Class aptent
      taciti sociosqu ad litora torquent per conubia nostra, per inceptos
      himenaeos. Nam ac vestibulum dolor. Etiam rhoncus turpis tortor, a
      faucibus libero dictum vel. Maecenas varius varius nisi eu consectetur.
      Donec in turpis vestibulum, suscipit neque ut, viverra magna. Sed
      ultricies sollicitudin porttitor. Morbi sollicitudin nisi nec magna
      dictum, a cursus metus eleifend. Donec rutrum diam dolor, nec fringilla
      est tristique quis.
    </p>
    <PanelHighlight>
      Nunc vel ullamcorper felis. Curabitur ullamcorper lorem id dolor pulvinar,
      vitae aliquet mauris convallis. Donec blandit purus lectus, in mattis elit
      luctus vitae. Donec lobortis velit tortor. Morbi quis sapien at quam
      blandit consequat. Praesent aliquam felis eu nisi aliquet, quis posuere
      nulla tempus. Duis faucibus lacinia enim, non varius orci egestas ut.
      Nulla at tortor auctor, eleifend sem at, egestas dui. In pharetra nulla a
      libero ultricies, vitae consequat diam tempus. Nulla placerat augue
      libero, eget ullamcorper massa accumsan non.
    </PanelHighlight>
    <img class="w-full mt-8" src="/assets/desert2.png" />
    <p>
      Integer ut lacus nec orci consectetur venenatis. Integer in velit
      convallis neque auctor varius rhoncus ultricies justo. Nam at mauris
      consectetur quam aliquam sodales eget et purus. Praesent tristique
      suscipit mi luctus tincidunt. Quisque lobortis, augue at porta porta, diam
      elit facilisis libero, sit amet auctor dui leo et sem. Sed consectetur
      urna eu consectetur auctor. Suspendisse rhoncus velit non volutpat
      lobortis. Maecenas sagittis massa ultricies lacus consectetur, eget
      condimentum odio rutrum. Aliquam nunc nisl, finibus ac venenatis id,
      imperdiet at nulla. Etiam lobortis, risus sit amet iaculis pellentesque,
      urna lacus blandit odio, sed condimentum ex metus vel risus. Donec et
      mauris urna. Mauris maximus consequat fringilla. Sed ut tempus urna, a
      hendrerit risus. Duis bibendum ipsum ut nulla auctor mattis.
    </p>
  </main>
</template>

<script setup>
const props = defineProps(["text"]);
</script>

<style scoped>
main {
  margin: 4rem auto 0 auto;
}

p {
  margin: 2rem 0;
}
</style>

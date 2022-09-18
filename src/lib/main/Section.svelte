<script>
    export let title;
    export let img;
</script>



<div class="flex flex-col mt-5  sm:flex-row  ">
    <div class=" w-full sm:w-[40%]  p-8 ">
        <img src={img} alt="img" class="rounded-md">
    </div>
    <div class="w-full sm:w-[60%] p-10 text-md sm:text-lg">
        <h2 class="mb-1 text-center sm:text-left ">
            {title}
        </h2>
        <p  class="text-center sm:text-left ">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aperiam numquam aliquid impedit deleniti esse laborum nobis quibusdam totam ad, nostrum, molestias unde eos, eaque laboriosam voluptatem perferendis omnis quo deserunt.
            molestias unde eos, eaque laboriosam voluptatem perferendis omnis quo deserunt.

        </p>
    </div>
</div>
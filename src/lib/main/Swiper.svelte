<script>
    // Import Swiper Svelte components
    import { Swiper, SwiperSlide } from "swiper/svelte";

    import "swiper/css/navigation";
    import "swiper/css/pagination";
    import "swiper/css/scrollbar";
    import "swiper/css";
    import Image from "./Image.svelte";
</script>

<Swiper class="cursor-grab" spaceBetween={50} slidesPerView={1}>
    <SwiperSlide
        ><Image
            bg="https://scontent.ftun15-1.fna.fbcdn.net/v/t39.30808-6/283872385_4864578140314314_1758536623256081244_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=e3f864&_nc_ohc=jlvvh2PU--4AX-nIZhR&tn=Gbs1HFHPFsyD4MkL&_nc_ht=scontent.ftun15-1.fna&oh=00_AT8KLI5sNjnGjd4yH5PJUym9TzdesCCt3-_KmIh7k32ZJQ&oe=632ACD79"
        /></SwiperSlide
    >
    <SwiperSlide
        ><Image
            bg="https://img.freepik.com/free-vector/hand-painted-watercolor-pastel-sky-background_23-2148902771.jpg?w=2000"
        /></SwiperSlide
    >
    <SwiperSlide
        ><Image
            bg="https://img.freepik.com/free-vector/hand-painted-watercolor-pastel-sky-background_23-2148902771.jpg?w=2000"
        /></SwiperSlide
    >
    <SwiperSlide
        ><Image
            bg="https://img.freepik.com/free-vector/hand-painted-watercolor-pastel-sky-background_23-2148902771.jpg?w=2000"
        /></SwiperSlide
    >
</Swiper>

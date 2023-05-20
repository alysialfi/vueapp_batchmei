<script>
export default {
    // name: ProductDisplay,
    data() {
        return {
            number: 1
        }
    },
    methods: {
        
    },
}
</script>

<template>
    <div class="flex">
        <!-- thumbnail -->
        <div class="w-1/2 h-screen bg-gray-200 flex justify-center items-center">
            <img src="../assets/thumbnail_sofa.png" alt="grey sofa thumbnail">
        </div>
        <!-- judul, desc, button -->
        <div class="w-1/2 flex flex-col py-12 px-8 justify-between">
            <div>
                <h1 class="text-4xl font-bold">Greyana Sofa</h1>
                <p class="mt-4">Introducing the Greyana Sofa. The perfect combination of style and comfort. With its sleek and modern design, this sofa is a statement piece that will elevate any living space. The Greyana Sofa features a stunning grey upholstery that is both soft to the touch and durable for everyday use. Crafted with a sturdy wooden frame and high-density foam cushions, the Greyana Sofa offers unbeatable comfort and support. The seat and back cushions are also removable and reversible, making it easy to maintain and keep looking like new.</p>
            </div>
            <div>
                <div>
                    <div class="text-3xl font-semibold">$75</div>
                    <div class="flex">
                        <button class="w-8 h-8 bg-black text-white">-</button>
                        <div class="w-8 h-8 text-center pt-1 bg-gray-200">0</div>
                        <button class="w-8 h-8 bg-black text-white">+</button>
                    </div>
                </div>
                <div>
                    <div class="text-xl font-semibold mb-2 mt-12">Subtotal</div>
                    <div class="flex gap-4">
                        <button class="bg-black w-1/2 h-12 text-white">Buy Now</button>
                        <button class="bg-black w-1/2 text-white">Add to cart</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
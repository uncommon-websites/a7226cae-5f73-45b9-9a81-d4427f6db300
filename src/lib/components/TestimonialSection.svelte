<script>
    import { ArrowLeft, ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-[#F9F7F2] py-24 overflow-hidden">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Navigation Buttons -->
        <div class="flex justify-end gap-2 mb-8">
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowLeft size={16} />
            </button>
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowRight size={16} />
            </button>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <!-- Quote Content -->
            <div class="pr-8">
                <div class="mb-8">
                    <span class="text-sm font-bold tracking-widest uppercase">NOMURA</span>
                </div>
                <blockquote class="text-2xl md:text-3xl font-light text-gray-900 leading-relaxed mb-12">
                    "Our strategic integration of Rogo transforms how we deliver value to clients. Rogo enables our teams to analyze market data and identify opportunities with unprecedented speed and precision, while allowing our bankers to focus more deeply on client relationships and strategic advisory."
                </blockquote>
                <div>
                    <div class="font-medium text-gray-900">Patrice Maffre</div>
                    <div class="text-[10px] uppercase tracking-widest text-gray-500 mt-1">International Head of Investment Banking, Nomura</div>
                </div>
            </div>

            <!-- Image -->
            <div class="relative h-[600px] w-full overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?q=80&w=2071&auto=format&fit=crop" 
                    alt="Business people walking" 
                    class="absolute inset-0 h-full w-full object-cover grayscale contrast-125"
                />
            </div>
        </div>
    </div>
</section>

<script>
    const partners = [
        { name: "Syndicated Deal Data", icon: "📊" },
        { name: "Middle Market Comps", icon: "🏦", color: "bg-primary-600" },
        { name: "Club Deal Analytics", icon: "C", color: "bg-primary-700" },
        { name: "Pricing Intelligence", icon: "P", color: "bg-primary-800" },
        { name: "Lender Networks", icon: "L", color: "bg-gray-700" },
        { name: "Market Structure Data", icon: "M", color: "bg-gray-800" },
        { name: "Covenant Analysis", icon: "📋" },
        { name: "Industry Benchmarks", icon: "🏭" },
        { name: "Credit Metrics", icon: "📈" },
        { name: "Term Sheet Library", icon: "📄" },
        { name: "Deal Flow Tracking", icon: "🔄" },
        { name: "Anonymized Comps", icon: "🔒" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Comprehensive Market Coverage</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                DealData captures the middle market and club deal ecosystem that existing data sources miss. We aggregate anonymized, structured comps from across the syndicated lending market to give you the benchmarks you need.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>

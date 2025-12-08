<script>
    const partners = [
        { name: "Your Firm's Data", icon: "🏢" },
        { name: "LSEG", icon: "🔵", color: "bg-blue-600" },
        { name: "Dow Jones", icon: "D", color: "bg-blue-400" },
        { name: "FactSet", icon: "F", color: "bg-blue-800" },
        { name: "Capital IQ", icon: "S", color: "bg-red-600" },
        { name: "PitchBook", icon: "P", color: "bg-blue-900" },
        { name: "Preqin", icon: "P", color: "bg-purple-900" },
        { name: "Real-time Web & News", icon: "🌐" },
        { name: "SEC Filings", icon: "🏛️" },
        { name: "Transcripts", icon: "📞" },
        { name: "Investor Presentations", icon: "📊" },
        { name: "International Filings", icon: "🌍" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Trusted Data</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                We partner with trusted data providers to bring the highest-quality financial information to our platform. Their expertise, combined with Rogo's technology, gives customers the clarity and confidence they need to move fast.
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

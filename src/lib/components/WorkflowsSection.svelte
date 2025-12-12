<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Stop Relying on Gut Instinct<br />Start Using Real Data
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Pricing Benchmarks -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-primary-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">$150M Club Deal Comps</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-primary-700">
                                <Check size={12} /> <span class="text-gray-600">12 comparable deals found</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Avg spread: L+425</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Leverage: 4.2x - 5.1x</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Similar industry/structure</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Pricing Benchmarks</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Access structured, anonymized comps that show exactly where your deals stand in the market. See pricing, structure, and lender appetite across comparable transactions in the middle market and club space.
                </p>
            </div>

            <!-- Card 2: Deal Intelligence -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Healthcare Sector Pricing Trends</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-700 rounded flex items-center justify-center text-white text-[8px]">DD</div>
                            <span class="text-[10px] text-gray-400">28 deals analyzed</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Deal Size</div>
                                <div class="col-span-2 text-right">Avg Spread</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> $50-100M</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> $100-200M</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> $200M+</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded w-1/2 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Deal Intelligence</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Understand market trends, lender appetite, and structural terms across your target segments. Filter by industry, size, leverage, and more to find the most relevant comparables for your deals.
                </p>
            </div>

            <!-- Card 3: Market Visibility -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-700 rounded flex items-center justify-center text-white text-[8px]">CC</div>
                            <span class="text-[10px] text-gray-500">Credit Committee Package</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Market comps for your $175M healthcare deal with defensible pricing analysis and lender appetite data.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Comparable Deals.pdf</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-700 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Pricing Analysis.xlsx</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Market Visibility</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Replace manual spreadsheets and anecdotal memory with a trusted, centralized platform. Get the clarity you need to defend your pricing and terms with confidence to credit committees and clients.
                </p>
            </div>
        </div>
    </div>
</section>

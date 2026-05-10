# probreakout-ea-website
website for proreakout EA
export default function ProBreakoutEALandingPage() {
  return (
    <div className="min-h-screen bg-black text-white">
      {/* Hero Section */}
      <section className="px-6 py-20 max-w-7xl mx-auto">
        <div className="grid lg:grid-cols-2 gap-12 items-center">
          <div>
            <div className="inline-block px-4 py-2 rounded-full border border-zinc-700 text-sm text-zinc-300 mb-6">
              Automated Forex Trading System
            </div>

            <div className="flex items-center gap-4 mb-6">
              <div className="w-16 h-16 rounded-2xl bg-white text-black flex items-center justify-center text-2xl font-black shadow-2xl">
                PB
              </div>

              <div className="px-4 py-2 rounded-xl border border-zinc-700 bg-zinc-900 text-sm text-zinc-300">
                ProBreakout EA
              </div>
            </div>

            <h1 className="text-5xl lg:text-7xl font-bold leading-tight mb-6">
              ProBreakout
              <span className="block text-zinc-400">EA System</span>
            </h1>

            <p className="text-zinc-300 text-lg leading-relaxed mb-8 max-w-xl">
              Algorithmic forex trading focused on controlled risk, swing-based entries,
              and long-term consistency. Built for prop firm evaluations and funded accounts.
            </p>

            <div className="flex flex-wrap gap-4 mb-10">
              <button className="px-8 py-4 rounded-2xl bg-white text-black font-semibold hover:scale-105 transition">
                View Performance
              </button>

              <button className="px-8 py-4 rounded-2xl border border-zinc-700 hover:border-zinc-500 transition">
                MyFxBook Stats
              </button>
            </div>

            <div className="grid grid-cols-3 gap-4 max-w-lg">
              <div className="bg-zinc-900 rounded-2xl p-4 border border-zinc-800">
                <div className="text-3xl font-bold">6+</div>
                <div className="text-zinc-400 text-sm mt-1">Months Testing</div>
              </div>

              <div className="bg-zinc-900 rounded-2xl p-4 border border-zinc-800">
                <div className="text-3xl font-bold">190+</div>
                <div className="text-zinc-400 text-sm mt-1">Executed Trades</div>
              </div>

              <div className="bg-zinc-900 rounded-2xl p-4 border border-zinc-800">
                <div className="text-3xl font-bold">Low DD</div>
                <div className="text-zinc-400 text-sm mt-1">Risk Focused</div>
              </div>
            </div>
          </div>

          <div className="relative">
            <div className="absolute inset-0 bg-zinc-800 blur-3xl opacity-20 rounded-full"></div>

            <div className="relative bg-zinc-900 border border-zinc-800 rounded-3xl p-8 shadow-2xl">
              <div className="flex items-center justify-between mb-8">
                <div>
                  <div className="text-zinc-400 text-sm">Live Demo Account</div>
                  <div className="text-2xl font-bold">EUR/USD Strategy</div>
                </div>

                <div className="w-4 h-4 bg-green-500 rounded-full animate-pulse"></div>
              </div>

              <div className="space-y-6">
                <div>
                  <div className="flex justify-between mb-2 text-sm">
                    <span className="text-zinc-400">Monthly Performance</span>
                    <span>+4.91%</span>
                  </div>
                  <div className="w-full bg-zinc-800 rounded-full h-3">
                    <div className="bg-white h-3 rounded-full w-2/3"></div>
                  </div>
                </div>

                <div>
                  <div className="flex justify-between mb-2 text-sm">
                    <span className="text-zinc-400">Win Protection</span>
                    <span>Break-even logic</span>
                  </div>
                  <div className="w-full bg-zinc-800 rounded-full h-3">
                    <div className="bg-white h-3 rounded-full w-4/5"></div>
                  </div>
                </div>

                <div>
                  <div className="flex justify-between mb-2 text-sm">
                    <span className="text-zinc-400">Risk Management</span>
                    <span>1 Trade Max</span>
                  </div>
                  <div className="w-full bg-zinc-800 rounded-full h-3">
                    <div className="bg-white h-3 rounded-full w-3/4"></div>
                  </div>
                </div>
              </div>

              <div className="mt-10 bg-black rounded-2xl p-6 border border-zinc-800">
                <div className="text-zinc-400 text-sm mb-2">Latest Position</div>
                <div className="flex justify-between items-center">
                  <div>
                    <div className="text-xl font-bold">EUR/USD</div>
                    <div className="text-zinc-500 text-sm">Swing Trade</div>
                  </div>

                  <div className="text-right">
                    <div className="text-2xl font-bold text-green-400">+42 pips</div>
                    <div className="text-zinc-500 text-sm">Running profit</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Features */}
      <section className="px-6 py-20 border-t border-zinc-900">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold mb-4">
              Built Around Real Trading Logic
            </h2>

            <p className="text-zinc-400 max-w-2xl mx-auto text-lg">
              Designed to survive long-term market conditions with disciplined execution,
              conservative exposure, and trend-based positioning.
            </p>
          </div>

          <div className="grid md:grid-cols-3 gap-6">
            <div className="bg-zinc-900 border border-zinc-800 rounded-3xl p-8">
              <div className="text-2xl mb-4">📉</div>
              <h3 className="text-2xl font-bold mb-4">Controlled Drawdown</h3>
              <p className="text-zinc-400 leading-relaxed">
                Strict risk management with limited exposure and protection against overtrading.
              </p>
            </div>

            <div className="bg-zinc-900 border border-zinc-800 rounded-3xl p-8">
              <div className="text-2xl mb-4">⚡</div>
              <h3 className="text-2xl font-bold mb-4">Break-even Protection</h3>
              <p className="text-zinc-400 leading-relaxed">
                Positions automatically secure capital once momentum confirms the move.
              </p>
            </div>

            <div className="bg-zinc-900 border border-zinc-800 rounded-3xl p-8">
              <div className="text-2xl mb-4">📊</div>
              <h3 className="text-2xl font-bold mb-4">Swing Trading System</h3>
              <p className="text-zinc-400 leading-relaxed">
                Focused on high-quality market structure instead of overtrading small moves.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Pricing */}
      <section className="px-6 py-24 border-t border-zinc-900">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-16">
            <h2 className="text-5xl font-bold mb-4">
              Subscription Plans
            </h2>

            <p className="text-zinc-400 text-lg max-w-2xl mx-auto">
              Flexible access plans for traders interested in following the ProBreakout EA strategy.
            </p>
          </div>

          <div className="grid md:grid-cols-4 gap-6">
            <div className="bg-zinc-900 border border-zinc-800 rounded-3xl p-8 text-center">
              <div className="text-zinc-400 mb-2">Starter</div>
              <div className="text-5xl font-bold mb-4">$50</div>
              <div className="text-zinc-500 mb-6">1 Week</div>

              <ul className="space-y-3 text-zinc-300 text-sm mb-8">
                <li>✔ EA Access</li>
                <li>✔ Trade Signals</li>
                <li>✔ Risk Settings</li>
              </ul>

              <button className="w-full py-3 rounded-2xl bg-white text-black font-semibold hover:scale-105 transition">
                Get Access
              </button>
            </div>

            <div className="bg-zinc-900 border border-zinc-800 rounded-3xl p-8 text-center">
              <div className="text-zinc-400 mb-2">Monthly</div>
              <div className="text-5xl font-bold mb-4">$120</div>
              <div className="text-zinc-500 mb-6">1 Month</div>

              <ul className="space-y-3 text-zinc-300 text-sm mb-8">
                <li>✔ Full EA Access</li>
                <li>✔ Setup Support</li>
                <li>✔ Performance Updates</li>
              </ul>

              <button className="w-full py-3 rounded-2xl bg-white text-black font-semibold hover:scale-105 transition">
                Subscribe
              </button>
            </div>

            <div className="bg-white text-black rounded-3xl p-8 text-center scale-105 shadow-2xl">
              <div className="mb-2 font-medium">Popular</div>
              <div className="text-5xl font-bold mb-4">$300</div>
              <div className="text-zinc-700 mb-6">3 Months</div>

              <ul className="space-y-3 text-sm mb-8">
                <li>✔ Priority Access</li>
                <li>✔ Advanced Settings</li>
                <li>✔ Private Support</li>
              </ul>

              <button className="w-full py-3 rounded-2xl bg-black text-white font-semibold hover:scale-105 transition">
                Start Now
              </button>
            </div>

            <div className="bg-zinc-900 border border-zinc-800 rounded-3xl p-8 text-center">
              <div className="text-zinc-400 mb-2">Professional</div>
              <div className="text-5xl font-bold mb-4">$1000</div>
              <div className="text-zinc-500 mb-6">1 Year</div>

              <ul className="space-y-3 text-zinc-300 text-sm mb-8">
                <li>✔ Long-Term Access</li>
                <li>✔ All Future Updates</li>
                <li>✔ VIP Support</li>
              </ul>

              <button className="w-full py-3 rounded-2xl bg-white text-black font-semibold hover:scale-105 transition">
                Go Pro
              </button>
            </div>
          </div>

          <div className="mt-16 bg-zinc-900 border border-zinc-800 rounded-3xl p-10">
            <h3 className="text-3xl font-bold mb-4">
              Copy Trading Integration
            </h3>

            <p className="text-zinc-400 text-lg leading-relaxed max-w-4xl">
              Subscribers can connect their MetaTrader account through a trade copier system.
              When the EA opens a position on the master account, subscribers instantly receive the same trade automatically on their own account.
              This allows fully automated copy trading without manually entering positions.
            </p>
          </div>
        </div>
      </section>

      {/* CTA */}
      <section className="px-6 py-24">
        <div className="max-w-5xl mx-auto text-center bg-zinc-900 border border-zinc-800 rounded-[40px] p-12">
          <h2 className="text-5xl font-bold mb-6">
            Built for Long-Term Consistency
          </h2>

          <p className="text-zinc-400 text-lg max-w-2xl mx-auto mb-10">
            Transparent testing. Real statistics. Risk-first philosophy.
            No unrealistic promises.
          </p>

          <div className="flex flex-wrap justify-center gap-4">
            <button className="px-8 py-4 rounded-2xl bg-white text-black font-semibold hover:scale-105 transition">
              Request MyFxBook Access
            </button>

            <button className="px-8 py-4 rounded-2xl border border-zinc-700 hover:border-zinc-500 transition">
              Contact
            </button>
          </div>
        </div>
      </section>
    </div>
  )
}

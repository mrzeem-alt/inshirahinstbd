export default function InshirahInstituteWebsite() { return ( <div className="min-h-screen bg-gray-100 text-gray-800"> <header className="bg-green-700 text-white py-6 shadow-lg"> <div className="max-w-6xl mx-auto px-4 flex flex-col md:flex-row items-center justify-between"> <div> <h1 className="text-4xl font-bold">Inshirah Institute BD</h1> <p className="text-lg mt-2">Modern Islamic & Academic Learning Platform</p> </div> <a
href="#contact"
className="mt-4 md:mt-0 bg-white text-green-700 px-5 py-2 rounded-2xl font-semibold shadow"
> যোগাযোগ করুন </a> </div> </header>

<section className="bg-white py-16">
    <div className="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h2 className="text-5xl font-bold leading-tight">
          ইসলামি ও আধুনিক শিক্ষার সুন্দর সমন্বয়
        </h2>
        <p className="mt-6 text-lg text-gray-600 leading-8">
          Inshirah Institute BD শিক্ষার্থীদের জন্য কুরআন, আরবি ভাষা,
          ইসলামি জ্ঞান এবং আধুনিক একাডেমিক শিক্ষার সমন্বয়ে একটি উন্নত
          শিক্ষা প্ল্যাটফর্ম।
        </p>
        <button className="mt-8 bg-green-700 text-white px-6 py-3 rounded-2xl text-lg shadow-lg hover:scale-105 transition">
          ভর্তি চলমান
        </button>
      </div>

      <div>
        <img
          src="https://images.unsplash.com/photo-1513258496099-48168024aec0?q=80&w=1200&auto=format&fit=crop"
          alt="Students"
          className="rounded-3xl shadow-2xl"
        />
      </div>
    </div>
  </section>

  <section className="py-16 bg-gray-50">
    <div className="max-w-6xl mx-auto px-4">
      <h3 className="text-3xl font-bold text-center mb-12">আমাদের কোর্সসমূহ</h3>

      <div className="grid md:grid-cols-3 gap-8">
        <div className="bg-white p-6 rounded-3xl shadow-lg">
          <h4 className="text-2xl font-semibold mb-4">আরবি ভাষা শিক্ষা</h4>
          <p className="text-gray-600 leading-7">
            নাহু, সরফ, আরবি সাহিত্য ও স্পোকেন আরবি শেখার পূর্ণাঙ্গ কোর্স।
          </p>
        </div>

        <div className="bg-white p-6 rounded-3xl shadow-lg">
          <h4 className="text-2xl font-semibold mb-4">কুরআন ও তাজবিদ</h4>
          <p className="text-gray-600 leading-7">
            সহিহ তিলাওয়াত, তাজবিদ এবং হিফজের বিশেষ যত্নসহকারে পাঠদান।
          </p>
        </div>

        <div className="bg-white p-6 rounded-3xl shadow-lg">
          <h4 className="text-2xl font-semibold mb-4">একাডেমিক সাপোর্ট</h4>
          <p className="text-gray-600 leading-7">
            স্কুল-কলেজ শিক্ষার্থীদের জন্য ইংরেজি ও সাধারণ শিক্ষার সহায়তা।
          </p>
        </div>
      </div>
    </div>
  </section>

  <section className="py-16 bg-white">
    <div className="max-w-6xl mx-auto px-4 text-center">
      <h3 className="text-3xl font-bold mb-6">কেন Inshirah Institute BD?</h3>

      <div className="grid md:grid-cols-4 gap-6 mt-10">
        <div className="bg-gray-100 rounded-3xl p-6 shadow">
          <h4 className="text-xl font-bold mb-3">অভিজ্ঞ শিক্ষক</h4>
          <p>যোগ্য ও দক্ষ শিক্ষকমণ্ডলী দ্বারা পাঠদান।</p>
        </div>

        <div className="bg-gray-100 rounded-3xl p-6 shadow">
          <h4 className="text-xl font-bold mb-3">অনলাইন ক্লাস</h4>
          <p>ঘরে বসেই লাইভ ও রেকর্ডেড ক্লাস সুবিধা।</p>
        </div>

        <div className="bg-gray-100 rounded-3xl p-6 shadow">
          <h4 className="text-xl font-bold mb-3">স্মার্ট সিলেবাস</h4>
          <p>সহজ ও আধুনিক পদ্ধতিতে পাঠদান।</p>
        </div>

        <div className="bg-gray-100 rounded-3xl p-6 shadow">
          <h4 className="text-xl font-bold mb-3">গাইডলাইন</h4>
          <p>শিক্ষার্থীদের নিয়মিত মূল্যায়ন ও পরামর্শ।</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" className="bg-green-700 text-white py-16">
    <div className="max-w-4xl mx-auto px-4 text-center">
      <h3 className="text-3xl font-bold mb-6">যোগাযোগ</h3>
      <p className="text-lg leading-8">
        ফোন: 01834611241
        <br />
        ইমেইল: info@inshirahinstbd.com
      </p>

      <button className="mt-8 bg-white text-green-700 px-6 py-3 rounded-2xl font-semibold shadow-lg">
        এখনই যোগাযোগ করুন
      </button>
    </div>
  </section>

  <footer className="bg-black text-white py-6 text-center">
    <p>
      © 2026 Inshirah Institute BD — All Rights Reserved
    </p>
  </footer>
</div>

); }

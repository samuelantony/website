export default function Home() {
  return (
    // Main container for the entire webpage content
    <main className="min-h-screen bg-white text-gray-800">

      {/* Hero section with a gradient background and call-to-action buttons */}
      <section className="bg-gradient-to-r from-blue-600 to-indigo-700 text-white py-20 px-6 text-center">
        <h1 className="text-4xl md:text-6xl font-bold mb-4">
          Recruitment That Moves with the Future
        </h1>
        <p className="text-lg md:text-2xl mb-6 max-w-2xl mx-auto">
          SAM Mobility & Tech connects top tech and mobility talent with companies driving change.
        </p>
        <div className="flex justify-center gap-4">
          {/* CTA button for clients */}
          <button className="bg-white text-blue-700 px-6 py-3 rounded-xl font-semibold hover:bg-gray-100 transition">
            Hire Talent
          </button>
          {/* CTA button for candidates */}
          <button className="bg-indigo-900 px-6 py-3 rounded-xl font-semibold hover:bg-indigo-800 transition">
            Find a Job
          </button>
        </div>
      </section>

      {/* Services section with three service offerings */}
      <section className="py-16 px-6 max-w-5xl mx-auto text-center">
        <h2 className="text-3xl font-bold mb-6">Our Services</h2>
        <div className="grid md:grid-cols-3 gap-8">
          {/* Service 1: Permanent Recruitment */}
          <div className="bg-gray-50 p-6 rounded-2xl shadow-sm">
            <h3 className="text-xl font-semibold mb-2">Permanent Recruitment</h3>
            <p>We find the right people for long-term success in your business.</p>
          </div>

          {/* Service 2: Contract Staffing */}
          <div className="bg-gray-50 p-6 rounded-2xl shadow-sm">
            <h3 className="text-xl font-semibold mb-2">Contract Staffing</h3>
            <p>Need flexible talent fast? We deliver skilled contractors quickly.</p>
          </div>

          {/* Service 3: Diversity Hiring Strategy */}
          <div className="bg-gray-50 p-6 rounded-2xl shadow-sm">
            <h3 className="text-xl font-semibold mb-2">Diversity Hiring Strategy</h3>
            <p>We embed inclusion into every hiring stage with targeted sourcing strategies.</p>
          </div>
        </div>
      </section>

      {/* Dual-column section for employers and job seekers */}
      <section className="bg-blue-50 py-16 px-6">
        <div className="max-w-5xl mx-auto grid md:grid-cols-2 gap-12">

          {/* Employers section */}
          <div>
            <h2 className="text-3xl font-bold mb-4">For Employers</h2>
            <p className="mb-4">
              Partner with a recruitment agency that understands the evolving tech and mobility markets. We support companies in:
            </p>
            <ul className="list-disc list-inside space-y-2">
              <li>EV & Automotive Tech</li>
              <li>SaaS, AI & Cloud Infrastructure</li>
              <li>Robotics & Smart Mobility</li>
            </ul>
          </div>

          {/* Job Seekers section */}
          <div>
            <h2 className="text-3xl font-bold mb-4">For Job Seekers</h2>
            <p className="mb-4">
              We help you find roles that match your skills and career goals, with support at every stage:
            </p>
            <ul className="list-disc list-inside space-y-2">
              <li>CV Guidance & Review</li>
              <li>Interview Coaching</li>
              <li>Regular Feedback & Communication</li>
            </ul>
          </div>
        </div>
      </section>

      {/* Contact section with email and phone information */}
      <section className="py-16 px-6 text-center">
        <h2 className="text-3xl font-bold mb-4">Let’s Talk Talent</h2>
        <p className="mb-6">
          Whether you're hiring or job hunting, we're ready to help.
        </p>
        <p className="text-lg font-medium">📩 hello@sammobilitytech.co.uk</p>
        <p className="text-lg">📞 +44 XXX XXX XXX</p>
      </section>

    </main>
  );
}


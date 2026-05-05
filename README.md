export default function Portfolio() {
  const skills = [
    'Java',
    'Selenium WebDriver',
    'TestNG',
    'Manual Testing',
    'API Testing',
    'Postman',
    'Regression Testing',
    'Smoke Testing',
    'Functional Testing',
    'Agile / Scrum',
    'Rally'
  ];
 
  const projects = [
    {
      title: 'Insurance Domain Testing – AIG Insurance Group',
      description:
        'Worked on Quality Engineering and Assurance processes for insurance applications by designing and executing manual and automated test cases.',
      tools: 'Selenium, Java, TestNG, Postman'
    },
    {
      title: 'Automation Framework Development',
      description:
        'Built and maintained automation frameworks using Page Object Model (POM), data-driven testing, and keyword-driven testing approaches.',
      tools: 'Selenium WebDriver, Java, Maven'
    },
    {
      title: 'API Testing Project',
      description:
        'Performed API validation using Postman including request validation, response verification, and collection execution.',
      tools: 'Postman, API Testing'
    }
  ];
 
  return (
    <div className="min-h-screen bg-gray-100 text-gray-800">
      {/* Header */}
      <header className="bg-blue-800 text-white py-16 px-6 text-center shadow-lg">
        <h1 className="text-5xl font-bold mb-4">Gyaneshwari Kamle</h1>
        <p className="text-xl font-medium">
          Quality Test Analyst | Manual and Automation Tester
        </p>
        <p className="mt-4 text-lg">Bengaluru, Karnataka</p>
      </header>
 
      {/* About Me */}
      <section className="max-w-6xl mx-auto px-6 py-12">
        <div className="bg-white rounded-3xl shadow-md p-8">
          <h2 className="text-3xl font-bold mb-6">About Me</h2>
          <p className="text-lg leading-8">
            I have 3.2 years of experience as a Quality Test Analyst at Cognizant
            Technology Solutions, specializing in Quality Engineering and
            Assurance (QEA). I possess hands-on experience in test automation
            using Selenium with Java, along with strong expertise in manual
            testing and API testing using Postman.
          </p>
 
          <p className="text-lg leading-8 mt-6">
            I have worked on insurance domain applications for AIG Insurance
            Group, where I analyzed requirements, designed comprehensive test
            cases, executed automation scripts, and ensured software quality by
            following Agile methodologies.
          </p>
        </div>
      </section>
 
      {/* Skills */}
      <section className="max-w-6xl mx-auto px-6 pb-12">
        <div className="bg-white rounded-3xl shadow-md p-8">
          <h2 className="text-3xl font-bold mb-6">Technical Skills</h2>
 
          <div className="grid grid-cols-2 md:grid-cols-3 gap-4">
            {skills.map((skill, index) => (
              <div
                key={index}
                className="bg-blue-100 text-blue-900 rounded-2xl py-3 px-4 text-center font-medium"
              >
                {skill}
              </div>
            ))}
          </div>
        </div>
      </section>
 
      {/* Experience */}
      <section className="max-w-6xl mx-auto px-6 pb-12">
        <div className="bg-white rounded-3xl shadow-md p-8">
          <h2 className="text-3xl font-bold mb-6">Professional Experience</h2>
 
          <div>
            <h3 className="text-2xl font-semibold">
              Cognizant Technology Solutions
            </h3>
            <p className="text-lg mt-2 mb-4">
              Manual and Automation Test Engineer (2023 – Present)
            </p>
 
            <ul className="list-disc ml-6 space-y-3 text-lg leading-8">
              <li>
                Worked on insurance domain projects for AIG Insurance Group.
              </li>
              <li>
                Analyzed business requirements and designed scalable test cases.
              </li>
              <li>
                Executed manual and automated test cases for web applications.
              </li>
              <li>
                Developed automation scripts using Selenium with Java and TestNG.
              </li>
              <li>
                Built frameworks using Page Object Model (POM).
              </li>
              <li>
                Performed regression, smoke, functional, integration, and end-to-end testing.
              </li>
              <li>
                Conducted API testing using Postman.
              </li>
              <li>
                Collaborated with developers and business teams to track and resolve defects.
              </li>
            </ul>
          </div>
        </div>
      </section>
 
      {/* Projects */}
      <section className="max-w-6xl mx-auto px-6 pb-12">
        <div className="bg-white rounded-3xl shadow-md p-8">
          <h2 className="text-3xl font-bold mb-6">Projects</h2>
 
          <div className="grid md:grid-cols-2 gap-6">
            {projects.map((project, index) => (
              <div
                key={index}
                className="border border-gray-200 rounded-2xl p-6 hover:shadow-xl transition duration-300"
              >
                <h3 className="text-2xl font-semibold mb-3">
                  {project.title}
                </h3>
 
                <p className="text-lg leading-7 mb-4">
                  {project.description}
                </p>
 
                <p className="font-medium text-blue-700">
                  Tools Used: {project.tools}
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>
 
      {/* Achievements */}
      <section className="max-w-6xl mx-auto px-6 pb-12">
        <div className="bg-white rounded-3xl shadow-md p-8">
          <h2 className="text-3xl font-bold mb-6">Achievements</h2>
 
          <ul className="list-disc ml-6 space-y-3 text-lg leading-8">
            <li>
              Automated regression test cases using Selenium with Java.
            </li>
            <li>
              Improved release speed by reducing manual testing effort.
            </li>
            <li>
              Identified critical defects before production release.
            </li>
            <li>
              Increased test coverage using data-driven testing approaches.
            </li>
            <li>
              Successfully delivered testing tasks within Agile sprint timelines.
            </li>
          </ul>
        </div>
      </section>
 
      {/* Education */}
      <section className="max-w-6xl mx-auto px-6 pb-12">
        <div className="bg-white rounded-3xl shadow-md p-8">
          <h2 className="text-3xl font-bold mb-6">Education</h2>
 
          <div>
            <h3 className="text-2xl font-semibold">
              Bachelor of Computer Applications (BCA)
            </h3>
            <p className="text-lg mt-2">
              Gogte Institute of Technology, Belgaum – 2022
            </p>
          </div>
        </div>
      </section>
 
      {/* Languages */}
      <section className="max-w-6xl mx-auto px-6 pb-12">
        <div className="bg-white rounded-3xl shadow-md p-8">
          <h2 className="text-3xl font-bold mb-6">Languages</h2>
 
          <div className="flex flex-wrap gap-4">
            <div className="bg-gray-200 px-6 py-3 rounded-2xl text-lg">
              English
            </div>
            <div className="bg-gray-200 px-6 py-3 rounded-2xl text-lg">
              Hindi
            </div>
            <div className="bg-gray-200 px-6 py-3 rounded-2xl text-lg">
              Marathi
            </div>
          </div>
        </div>
      </section>
 
      {/* Contact */}
      <section className="max-w-6xl mx-auto px-6 pb-16">
        <div className="bg-white rounded-3xl shadow-md p-8 text-center">
          <h2 className="text-3xl font-bold mb-6">Contact</h2>
 
          <p className="text-lg mb-3">
            Email: gyaneshwarikamle@gmail.com
          </p>
 
          <p className="text-lg mb-3">
            Phone: +91 7795770384
          </p>
 
          <p className="text-lg">
            Bengaluru, Karnataka
          </p>
        </div>
      </section>
 
      {/* Footer */}
      <footer className="bg-blue-800 text-white text-center py-6 text-lg">
        © 2026 Gyaneshwari Kamle | QA Automation Portfolio
      </footer>
    </div>
  );
}
 

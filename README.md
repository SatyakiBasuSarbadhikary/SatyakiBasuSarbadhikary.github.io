import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Github, Linkedin } from "lucide-react";

export default function Home() {
  return (
    <main className="bg-white text-black min-h-screen px-6 py-10 space-y-16">
      <section className="text-center">
        <h1 className="text-4xl font-bold">Satyaki Basu Sarbadhikary</h1>
        <p className="mt-2 text-lg">Incoming PhD Student, Statistics @ NUS Singapore</p>
        <p className="text-md text-gray-700 mt-1">Email: satyakibasusarbadhikary@gmail.com | Phone: +91 9007164450</p>
        <div className="flex justify-center gap-6 mt-4">
          <a href="https://github.com/SatyakiBasuSarbadhikary/Projects" target="_blank">
            <Github className="h-6 w-6" />
          </a>
          <a href="https://www.linkedin.com/in/satyaki-basu-sarbadhikary-2401a5234" target="_blank">
            <Linkedin className="h-6 w-6" />
          </a>
        </div>
      </section>
      <section>
        <h2 className="text-2xl font-semibold mb-4">About</h2>
        <p>
          I’m passionate about applying statistical methodologies to real-world challenges, with particular interest in
          spatial statistics, time series analysis, network theory, and machine learning. My current research explores
          structural breaks in spatial networks to understand dynamic changes in urban data.
        </p>
      </section>
      <section>
        <h2 className="text-2xl font-semibold mb-4">Research Interests</h2>
        <ul className="list-disc ml-6 space-y-1">
          <li>Time Series Analysis & Change Point Detection</li>
          <li>Spatial Statistics & Spatio-Temporal Models</li>
          <li>Network Analysis & Graph Theory</li>
          <li>Statistical Computing & Machine Learning</li>
        </ul>
      </section>
      <section>
        <h2 className="text-2xl font-semibold mb-4">Research Projects</h2>
        <Card className="mb-4">
          <CardContent className="pt-4">
            <h3 className="font-bold">UK Property Transactions – Structural Breaks in Spatial Networks</h3>
            <p className="text-sm text-gray-600">IIM Bangalore | Summer 2024 – Present</p>
            <p className="mt-2">
              A two-stage model involving LISA clustering and network Laplacians to detect structural breaks and develop a
              data-driven zoning strategy.
            </p>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="pt-4">
            <h3 className="font-bold">COVID-19 Government Messaging Analysis</h3>
            <p className="text-sm text-gray-600">IIM Bangalore | Fall 2024</p>
            <p className="mt-2">
              Network-based analysis of Indian government health newsletters using sentiment tracking, VAR modeling, and
              thematic linkages.
            </p>
          </CardContent>
        </Card>
      </section>
      <section>
        <h2 className="text-2xl font-semibold mb-4">Experience</h2>
        <ul className="list-disc ml-6 space-y-3">
          <li><strong>Research Associate</strong>, IIM Bangalore – Decision Sciences (Jul 2024–Present)</li>
          <li><strong>Research Intern</strong>, Indian Statistical Institute Kolkata – SQC & OR (Apr–Jun 2024)</li>
          <li><strong>Data Science Intern</strong>, TCG Digital (Jun–Jul 2023)</li>
        </ul>
      </section>
      <section>
        <h2 className="text-2xl font-semibold mb-4">Publications</h2>
        <ul className="list-disc ml-6 space-y-3">
          <li><strong>Creation of a novel ML-based supply chain approach</strong> – Under review in Springer Edited Book Series</li>
          <li><strong>COVID-19 Communication Strategy Analysis</strong> – Under review, ICA Conference 2025</li>
        </ul>
      </section>
      <section>
        <h2 className="text-2xl font-semibold mb-4">Skills</h2>
        <ul className="grid grid-cols-2 gap-4">
          <li><strong>R</strong> (Proficient)</li>
          <li><strong>Python</strong> (Working Proficiency)</li>
          <li><strong>SQL</strong> (Proficient)</li>
          <li><strong>LaTeX, MS Office</strong></li>
        </ul>
      </section>
      <footer className="text-center text-sm mt-12 text-gray-500">
        © 2025 Satyaki Basu Sarbadhikary. Built with ❤️ using React & Tailwind CSS.
      </footer>
    </main>
  );
}


# SatyakiBasuSarbadhikary.github.io
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Github, Linkedin } from "lucide-react";

export default function HomePage() {
  return (
    <div className="min-h-screen bg-white text-black p-6">
      <header className="text-center mb-10">
        <h1 className="text-4xl font-bold">Satyaki Basu Sarbadhikary</h1>
        <p className="text-lg">Research Associate – Indian Institute Of Management, Bangalore</p>
        <div className="mt-4 flex justify-center gap-4">
          <a href="tel:+919007164450" className="underline">+91 9007164450</a>
          <a href="mailto:satyakibasusarbadhikary@gmail.com" className="underline">Email</a>
          <a href="https://github.com/SatyakiBasuSarbadhikary/Projects" target="_blank"><Github /></a>
          <a href="https://www.linkedin.com/in/satyaki-basu-sarbadhikary-2401a5234" target="_blank"><Linkedin /></a>
        </div>
      </header>

      <section className="grid gap-6">
        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Objective</h2>
            <p>
              I am passionate about applying statistical methodologies to address complex real-world problems, with a
              focus on spatial statistics, time series analysis, network theory and machine learning. My research focuses
              on detecting structural breaks in spatial networks and analyzing dynamic data changes.
            </p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Research Interests</h2>
            <ul className="list-disc list-inside">
              <li>Time Series Analysis and Change Point Detection</li>
              <li>Spatial Statistics and Spatio-Temporal Models</li>
              <li>Network Analysis and Graph Theory</li>
              <li>Statistical Computing and Machine Learning</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Education</h2>
            <ul>
              <li>MSc Data Science – St. Xavier’s College Kolkata (2022–2024), CGPA: 7.98</li>
              <li>BSc (Hons.) Statistics – St. Xavier’s College Kolkata (2019–2022), CGPA: 7.88</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Certifications</h2>
            <p>Spatial Data Science and Applications – Yonsei University, South Korea (via Coursera), Dec 2024</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Experience</h2>
            <ul className="list-disc list-inside">
              <li><strong>IIM Bangalore</strong>: Detecting structural breaks in UK house price data using networks (Jul 2024 – Present)</li>
              <li><strong>Indian Statistical Institute</strong>: Supply chain optimization using XGBoost and simulation (Apr 2024 – Jun 2024)</li>
              <li><strong>TCG Digital</strong>: Data visualization and machine learning implementation (Jun 2023 – Jul 2023)</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Publications</h2>
            <ul className="list-disc list-inside">
              <li>Operational excellence in supply chain (Springer Book Series, under review)</li>
              <li>COVID-19 government messaging analysis (ICA Conference submission)</li>
              <li>Structural breaks in real estate networks (Manuscript in preparation)</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Conference</h2>
            <p>Advances in High-Dimensional Statistical Learning – IIT Bombay & NCSU, 2024</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-2xl font-semibold">Research Projects</h2>
            <ul className="list-disc list-inside">
              <li><strong>Structural Breaks in UK Property Transactions</strong> – LISA clustering, network Laplacians, localized pricing index</li>
              <li><strong>COVID-19 Management Strategies</strong> – Preferential attachment, VAR models, sentiment analysis</li>
            </ul>
          </CardContent>
        </Card>
      </section>
    </div>
  );
}

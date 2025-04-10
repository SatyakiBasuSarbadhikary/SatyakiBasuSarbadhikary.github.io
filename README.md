import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail, FileText, GraduationCap, Briefcase } from "lucide-react";

export default function Home() {
  return (
    <div className="min-h-screen bg-white text-black p-6 md:p-10">
      <div className="grid grid-cols-1 md:grid-cols-3 gap-10 items-start">
        <div className="md:col-span-1">
          <img
            src="/IIM_cubicle_pic.jpg"
            alt="Satyaki Basu Sarbadhikary"
            className="rounded-2xl shadow-lg w-full"
          />
        </div>
        <div className="md:col-span-2 space-y-6">
          <div>
            <h1 className="text-4xl font-bold mb-2">Satyaki Basu Sarbadhikary</h1>
            <p className="text-lg text-gray-700 mb-2">\              Research Associate, Indian Institute of Management Bangalore
            </p>
            <p className="text-sm text-gray-600">
              Email: satyaki.basu@iimb.ac.in | Phone: +91-6291429737
            </p>
            <Button
              className="mt-4"
              variant="outline"
              onClick={() => window.open("/MIZZOU_CV.pdf", "_blank")}
            >
              <FileText className="mr-2" /> View Full CV
            </Button>
          </div>
          <Card>
            <CardContent className="p-4 space-y-2">
              <h2 className="text-2xl font-semibold">Research Interests</h2>
              <ul className="list-disc list-inside text-gray-700">
                <li>Spatial Statistics</li>
                <li>Time Series and Structural Breaks</li>
                <li>Statistical Computing & Nonparametrics</li>
                <li>Machine Learning and Networks</li>
              </ul>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4 space-y-2">
              <h2 className="text-2xl font-semibold">Education</h2>
              <div>
                <h3 className="font-semibold">M.Sc. Data Science</h3>
                <p>St. Xavier's College, Kolkata – CGPA: 7.98</p>
              </div>
              <div>
                <h3 className="font-semibold">B.Sc. Statistics</h3>
                <p>St. Xavier's College, Kolkata – CGPA: 7.88</p>
              </div>
              <div>
                <h3 className="font-semibold">Post Graduate Diploma</h3>
                <p>Time Series Analysis – Indian Statistical Institute (Cohort 3)</p>
              </div>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4 space-y-2">
              <h2 className="text-2xl font-semibold">Experience</h2>
              <div>
                <h3 className="font-semibold">Research Associate</h3>
                <p>IIM Bangalore | Jul 2024 – Present</p>
                <p>
                  Working on structural break detection in spatial and temporal domains of UK house price data, clustering using LISA and K-Medoids, dynamic network construction, and Laplacian spectral analysis. Guided by Dr. Soudeep Deb.
                </p>
              </div>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4 space-y-2">
              <h2 className="text-2xl font-semibold">Projects</h2>
              <ul className="list-disc list-inside text-gray-700 space-y-1">
                <li>Gender Classification Using Voice Data</li>
                <li>Predicting Diabetes Onset Based on Diagnostics</li>
                <li>CLT Simulation via Monte Carlo in R</li>
                <li>Credit Card Fraud Detection</li>
              </ul>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4 space-y-2">
              <h2 className="text-2xl font-semibold">Academic Highlights</h2>
              <p>
                Secondary (ICSE): 97%, Higher Secondary (ISC): 96% — Math & Computer Science: 96%
              </p>
              <p>
                Coursework at ISI: Statistical Methods (Prof. Arnab Chakraborty), Time Series (Prof. Raju Maiti), Probability (Dr. Probal Chowdhury)
              </p>
            </CardContent>
          </Card>
        </div>
      </div>
    </div>
  );
}

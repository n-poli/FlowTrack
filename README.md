# FlowTrack

FlowTrack is a full-stack web application designed to simplify production tracking in manufacturing environments where traditional MES systems are often too complex and error-prone.

## 🚀 Overview

FlowTrack focuses on real-time tracking of production phases, helping operators and managers maintain visibility without adding unnecessary complexity to daily workflows.

## ⚠️ Problem

In many manufacturing environments:

* Operators forget to start or stop work phases
* Production data becomes unreliable
* Managers lack real-time visibility
* Existing MES systems are too rigid and difficult to use

## 💡 Solution

FlowTrack provides a simple and error-tolerant system to track production phases and working times.

Instead of enforcing rigid workflows, the system:

* Automatically handles missing inputs
* Detects anomalies in phase duration
* Suggests corrections or auto-closes phases

## 🧠 Key Idea

The goal is not perfect data input, but **reliable and usable data**.

FlowTrack is designed to adapt to human behavior, reducing friction and ensuring consistent tracking even in imperfect real-world conditions.

## ⚙️ Features (MVP)

* User authentication (admin / operator roles)
* Orders with multiple production phases
* Start / stop phase tracking
* Automatic time calculation
* Anomaly detection (e.g. unusually long phases)
* Smart suggestions for phase correction or closure

## 📊 Example

An operator starts a welding phase but forgets to stop it.

FlowTrack:

* Detects that the phase is taking longer than expected
* Sends a warning
* Suggests closing the phase automatically

This ensures accurate tracking without interrupting the workflow.

## 🛠️ Tech Stack

* Backend: Node.js + NestJS
* Frontend: React
* Database: PostgreSQL
* ORM: Prisma
* Authentication: JWT

## 📈 Future Improvements

* Adaptive time estimation based on historical data
* Confidence scoring for tracking reliability
* Advanced anomaly detection
* Integration with IoT / sensors
* Multi-company support

## 💼 Vision

To build a lightweight, intelligent alternative to traditional MES systems, focused on usability, flexibility, and real-world production needs.

## 🚧 Status

Work in progress

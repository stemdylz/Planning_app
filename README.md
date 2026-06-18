# Planning_app
Reno HQ — Home Renovation Project Management App

A lightweight, single-file progressive web app (PWA) built for managing a full home renovation across 14 site sections. Designed to run on iPad Pro as a home screen app with no fat-client installation required.

Features:

	•	14 area-based project sections with phases, tasks and action item checklists
	•	Collapsible project tree with 5 view levels (Sections → Phases → Tasks → Actions → Expand All)
	•	Inline double-click editing at every level — rename, redate, reorder
	•	Task status cycling (Not Started → In Progress → Blocked → Done)
	•	Overall and per-project completion tracking with live progress bars
	•	Interactive Site Map — upload a floor plan sketch, draw polygon zones over it, link zones to project sections, tap zones to view task status and capture ideas
	•	Ideas capture per zone with one-tap promotion to project tasks
	•	Gantt schedule view — dynamically generated from live project data
	•	Procurement checklist with priority grouping and order deadlines
	•	Dependency and sequencing rules board
	•	Google Sheets backend — auto-connects on load, writes all data to a linked spreadsheet via Apps Script
	•	localStorage as primary cache with Google Sheets as persistent cloud backup
	•	PWA manifest and service worker for offline use and home screen installation
	•	Light warm theme optimised for extended use

Stack: Vanilla HTML · CSS · JavaScript · Google Apps Script · No frameworks · No build tools · Single file deployment

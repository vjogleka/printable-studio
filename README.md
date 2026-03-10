# Printable Studio

Personal analytics and research tool for our Etsy printable template shop.

## What It Does

My wife and I sell printable wedding and event planning templates on Etsy — seating charts, itineraries, shower games, and more. Printable Studio helps us run our shop smarter:

- **Performance Tracking** — Reads our Etsy shop stats (views, favorites, sales) to see what's working
- **Niche Research** — Analyzes trending search terms and listing density to find underserved product opportunities
- **Listing Optimization** — Surfaces insights on which titles, tags, and categories drive the most traffic

## How It Works

- Built with **FastAPI** (backend) and **Next.js** (frontend)
- Uses the **Etsy Open API v3** for read-only shop data access
- Runs locally — all data stays on our machine
- No buyer data is collected or stored

## Status

Early development — setting up infrastructure and API integrations.

## API Usage

This application uses the Etsy Open API v3 with **read-only** access:
- Shop listing statistics
- Public listing and category data
- Search trend information

No write operations are performed. No buyer or customer data is accessed.

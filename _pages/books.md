---
title: "Books"
permalink: /books/
layout: single
author_profile: true
---

<style>
.books-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.book-card {
  display: flex;
  flex-direction: column;
  text-decoration: none !important;
  color: inherit !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  background: rgba(128, 128, 128, 0.05);
  border: 1px solid rgba(128, 128, 128, 0.1);
  border-radius: 8px;
  overflow: hidden;
}

.book-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.1);
}

html.dark-theme .book-card {
  background: #1e1e1e;
  border: 1px solid #333;
}

.book-cover-wrapper {
  width: 100%;
  aspect-ratio: 2 / 3;
  overflow: hidden;
  background-color: #f0f0f0;
}

html.dark-theme .book-cover-wrapper {
  background-color: #2a2a2a;
}

.book-cover {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.book-info {
  padding: 0.75rem 1rem;
}

.book-title {
  font-weight: 700;
  font-size: 0.95rem;
  line-height: 1.3;
  margin-bottom: 0.5rem;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
  text-transform: capitalize;
}

.book-author-label {
  font-size: 0.7rem;
  opacity: 0.6;
  margin-bottom: 1px;
}

.book-author-name {
  font-size: 0.8rem;
  opacity: 0.9;
}

</style>

<div class="books-grid">
  {% for book in site.books %}
  <a href="{{ book.url }}" class="book-card">
    <div class="book-cover-wrapper">
      {% if book.cover %}
      <img src="{{ book.cover }}" alt="{{ book.title }} Cover" class="book-cover" loading="lazy">
      {% else %}
      <div class="book-cover" style="display: flex; align-items: center; justify-content: center; padding: 1rem; text-align: center; font-size: 0.8rem; opacity: 0.5;">No Cover</div>
      {% endif %}
    </div>
    <div class="book-info">
      <div class="book-title">{{ book.title }}</div>
      <div class="book-author-label">author</div>
      <div class="book-author-name">{{ book.author }}</div>
    </div>
  </a>
  {% endfor %}
</div>

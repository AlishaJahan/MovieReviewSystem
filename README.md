# MovieReviewSystem
This project is a Movie Review System that allows users to manage and search through a collection of movies efficiently. It uses classic algorithms — Merge Sort, Quick Sort, and Binary Search
Key Features:

Sort Movies:

Merge Sort is used to sort the movie list based on criteria like movie name or rating in ascending order.

Quick Sort is used to sort movies in descending order based on rating or other attributes.

Search for a Movie:

After sorting the movie list (by title), Binary Search is used to quickly find a specific movie.

This significantly reduces search time compared to a simple linear search, especially when the list grows large.

View Movie Details: After searching, users can view the detailed information of the selected movie, including reviews and ratings.

Technologies & Concepts Used:
Binary Search: For fast lookup in a sorted list of movies.

Merge Sort: For stable, efficient ascending order sorting (O(n log n) time complexity).

Quick Sort: For fast and efficient descending order sorting.

Why These Algorithms?

Merge Sort guarantees O(n log n) time even in the worst case and is stable, keeping movies with the same ratings in the original order.

Quick Sort is usually faster on average for in-memory sorting, making it ideal for descending order operations where quick response is prioritized.

Binary Search provides O(log n) search time, making movie lookup extremely efficient compared to scanning through the entire list.
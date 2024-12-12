# ReaderApp
Use Combine Framework for reactive programming to handle API calls and user interactions smoothly. Use @Published properties in your ViewModel to bind the API data and settings filters to the SwiftUI views.

Key Features to Implement
a) Show Stories from API
	•	Fetch stories using Combine's URLSession.DataTaskPublisher.
	•	Decode the API response into a Story model using JSONDecoder.
	•	Update a @Published var stories: [Story] in the ViewModel to bind the stories to the UI.

# MediaSound

## Do you want a platform where you can listen to anything, without censorship and opting for free-speech, completely free?
Here, in MediaSound, we want to create a free-license platform to upload whatever you want to say and hear. We take people's safety and freedom seriously. Really

# Business

# 



## User Stories:

__As a__ _user_, __I want__ to access my personalized profile where I can view and edit my personal information, such as my name, email, and profile picture.
__As a__ _podcaster_, __I want__ to be able to upload audio files in some formats like MP3 and WAV to publish my podcasts.
__As a__ _system administrator_, __I want__ to implement a secure and scalable storage system to efficiently manage users' audio files.
__As a__ _user_, __I want__ to be able to leave comments and ratings on podcasts to interact with other users and content creators.
__As a__ _user_, __I want__ to be able to create personalized playlists, either public or private, to organize my favorite podcasts.
__As a__ _user_, __I want__ to be able to follow other content creator users to stay updated on their new releases.
__As a__ _user_, __I want__ playback controls such as play, pause, forward, rewind, volume adjustment, and to see the average rating and comments of a podcast while listening.
__As a__ _user_, __I want__ to be able to search for podcasts by title, description, user, tags, and categories.
__As a__ _user_, __I want__ to be able to get podcasts by categories, tags, popularity, and trends to discover new content.

## Entities:

__User:__ name, mail, password, profile, profile photo, info, preference, getName(), changeName(), getMail(), changeMail(), changePassword(), addInfo, changeInfo(), addPreference(), changePreference(), deleteUser()
__Podcaster:__ alias, rate, getPodcast()
__Podcast:__ author, uuidPodcast, genre, title, uploadDate, duration, program, description, audioQuality, format, tag, category, language, ratePodcast(), addPodcast(), deletePodcast(), hidePodcast(), getInfoPodcast()
__Playlist:__ name, uuidPlaylist, amountPodcast, descriptionPlaylist, addPlaylist(), deletePlaylist(), openPlaylist(), closePlaylist(), addPodcastPlaylist(), removePodcastPlaylist(), playPlaylist(), getAmountPlaylist()
__MediaPlayer:__ volume, playback, state, setVolume(), setPlayback(), playMedia(), pauseMedia(), getVolume(), getState(), queuePodcast(), getQueue(), loadPodcast(), getCurrentPodcast(), getCurrentTime()

## Processes:





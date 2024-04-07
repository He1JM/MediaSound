# MediaSound

## Do you want a platform where you can listen to anything, without censorship and opting for free-speech, completely free?

Here, in MediaSound, we want to create a free-license platform to upload whatever you want to say and hear. We take people's safety and freedom seriously. Really


# Business

# 



## User Stories:

__As a__ _user_, __I want__ to access my personalized profile __to that__ view and edit my personal information, such as my name, email, and profile picture.

__As a__ _podcaster_, __I want__ to be able to upload audio files in some formats like MP3 and WAV __to that__ publish my podcasts.

__As a__ _podcaster_, __I want__ to see the views, rating and comments of my podcasts __to that__ improve my content.

__As a__ _user_, __I want__ to be able to leave comments and ratings on podcasts __to that__ interact with other users and content creators.

__As a__ _user_, __I want__ to be able to create personalized playlists, either public or private, __to that__ organize my favorite podcasts.

__As a__ _user_, __I want__ to be able to follow other content creator users __to that__ stay updated on their new releases.

__As a__ _user_, __I want__ playback controls such as play, pause, forward, rewind, volume adjustment, __so that__ control the playback of the podcast.

__As a__ _user_, __I want__ to be able to search for podcasts by title, description, user, tags, and categories __so that__ find specific podcasts or discover new ones.

__As a__ _user_, __I want__ to be able to get podcasts recommendations by categories, tags, popularity, and trends __to that__ discover new content.


## Entities:

__User:__ name, mail, password, profile, profile photo, info, preference, getName(), changeName(), getMail(), changeMail(), changePassword(), addInfo, changeInfo(), addPreference(), changePreference(), deleteUser()

__Podcaster:__ alias, rate, getPodcast()

__Podcast:__ author, uuidPodcast, genre, title, uploadDate, duration, program, description, audioQuality, format, tag, category, language, ratePodcast(), addPodcast(), deletePodcast(), hidePodcast(), getInfoPodcast()

__Playlist:__ name, uuidPlaylist, amountPodcast, descriptionPlaylist, addPlaylist(), deletePlaylist(), openPlaylist(), closePlaylist(), addPodcastPlaylist(), removePodcastPlaylist(), playPlaylist(), getAmountPlaylist()

__MediaPlayer:__ volume, playback, state, setVolume(), setPlayback(), playMedia(), pauseMedia(), getVolume(), getState(), queuePodcast(), getQueue(), loadPodcast(), getCurrentPodcast(), getCurrentTime()


## Processes:






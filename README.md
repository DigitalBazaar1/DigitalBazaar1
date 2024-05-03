/**
 * @name Digital-Themes
 * @author s7ep.rar
 * @description A dark, rounded discord theme.
 * @version 1.6.2
 * @source https://github.com/refact0r/midnight-discord/blob/master/midnight.theme.css

/* IMPORTANT: make sure to enable dark mode in discord settings for the theme to apply properly!!! */

@import url('https://github.com/users/DigitalBazaar1/projects/1/views/1?filterQuery=Digital+Bazaar+Discord+Themes');

/* customize things here */
:root {
	/* font, change to 'gg sans' for default discord font*/
	--font: 'figtree';

	/* top left corner text */
	--corner-text: 'Digital Bazaar';

	/* color of status indicators and window controls */
	--online-indicator: #23a55a; /* change to #23a55a for default green */
	--dnd-indicator: #f13f43; /* change to #f13f43 for default red */
	--idle-indicator: #f0b232; /* change to #f0b232 for default yellow */
	--streaming-indicator: #593695; /* change to #593695 for default purple */

	/* accent colors */
	--accent-1: hsl(278, 100%, 50%); /* links */
	--accent-2: hsl(278, 100%, 50%); /* general unread/mention elements */
	--accent-3: hsl(278, 100%, 50%); /* accent buttons */
	--accent-4: hsl(278, 100%, 50%); /* accent buttons when hovered */
	--accent-5: hsl(278, 100%, 50%); /* accent buttons when clicked */
	--mention: hsla(256, 80%, 52%, 0.1); /* mentions & mention messages */
	--mention-hover: hsla((190, 80%, 52%, 0.05)); /* mentions & mention messages when hovered */

	/* text colors */
	--text-0: white; /* text on colored elements */
	--text-1: var(--text-2); /* other normally white text */
	--text-2: hsl(0, 0%, 100%); /* headings and important text */
	--text-3: hsl(0, 0%, 100%); /* normal text */
	--text-4: hsl(0, 0%, 100%); /* icon buttons and channels */
	--text-5: hsl(0, 100%, 50%); /* muted channels/chats and timestamps */

	/* background and dark colors */
	--bg-1: hsl(220, 15%, 20%); /* dark buttons when clicked */
	--bg-2: hsl(220, 15%, 16%); /* dark buttons */
	--bg-3: hsl(220, 15%, 13%); /* spacing, secondary elements */
	--bg-4: hsl(220, 15%, 10%); /* main background color */
	--hover: rgb(230, 20%, 40%, 0.1); /* channels and buttons when hovered */
	--active: rgb(220, 20%, 40%, 0.2); /* channels and buttons when clicked or selected */
	--message-hover: rgb(220, 0%, 0%, 0.1); /* messages when hovered */

	/* amount of spacing and padding */
	--spacing: 12px;

	/* animations */
	/* ALL ANIMATIONS CAN BE DISABLED WITH REDUCED MOTION IN DISCORD SETTINGS */
	--list-item-transition: 0.2s ease; /* channels/members/settings hover transition */
	--unread-bar-transition: 0.2s ease; /* unread bar moving into view transition */
	--moon-spin-transition: 0.4s ease; /* moon icon spin */
	--icon-spin-transition: 1s ease; /* round icon button spin (settings, emoji, etc.) */

	/* corner roundness (border-radius) */
	--roundness-xl: 22px; /* roundness of big panel outer corners */
	--roundness-l: 20px; /* popout panels */
	--roundness-m: 16px; /* smaller panels, images, embeds */
	--roundness-s: 12px; /* members, settings inputs */
	--roundness-xs: 10px; /* channels, buttons */
	--roundness-xxs: 8px; /* searchbar, small elements */

	/* direct messages moon icon */
	/* change to block to show, none to hide */
	--discord-icon: none; /* discord icon */
	--moon-icon: block; /* moon icon */
	--moon-icon-url: url('https://upload.wikimedia.org/wikipedia/commons/c/c4/Font_Awesome_5_solid_moon.svg'); /* custom icon url */
	--moon-icon-size: auto;

	/* filter uncolorable elements to fit theme */
	/* (just set to none, they're too much work to configure) */
	--login-bg-filter: saturate(0.3) hue-rotate(-15deg) brightness(0.4); /* login background artwork */
	--green-to-accent-3-filter: hue-rotate(56deg) saturate(1.43); /* add friend page explore icon */
	--blurple-to-accent-3-filter: hue-rotate(304deg) saturate(0.84) brightness(1.2); /* add friend page school icon */
}

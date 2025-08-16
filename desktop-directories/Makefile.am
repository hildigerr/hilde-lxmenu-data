NULL = 

directorydir = $(datadir)/desktop-directories
directory_in_files =				\
	ActionGames.directory.in                \
	AdventureGames.directory.in             \
	ArcadeGames.directory.in                \
	audio.directory.in                      \
	BoardGames.directory.in                 \
	CardGames.directory.in                  \
	KidsGames.directory.in                  \
	LogicGames.directory.in                 \
	RolePlayingGames.directory.in           \
	SimulationGames.directory.in            \
	SportsGames.directory.in                \
	StrategyGames.directory.in              \
	system-emulation.directory.in           \
	X-UnsortedGames.directory.in            \
	lxde-audio-video.directory.in           \
	lxde-development.directory.in           \
	lxde-education.directory.in             \
	lxde-game.directory.in                  \
	lxde-graphics.directory.in              \
	lxde-menu-applications.directory.in     \
	lxde-network.directory.in               \
	lxde-office.directory.in                \
	lxde-other.directory.in                 \
	lxde-science.directory.in               \
	lxde-settings.directory.in              \
	lxde-settings-system.directory.in              \
	lxde-system.directory.in                \
	lxde-utility.directory.in               \
	lxde-utility-accessibility.directory.in \
	$(NULL)

directory_DATA = $(directory_in_files:.directory.in=.directory)
@INTLTOOL_DIRECTORY_RULE@

EXTRA_DIST = $(directory_in_files) $(directory_DATA)

DISTCLEANFILES = $(directory_DATA)

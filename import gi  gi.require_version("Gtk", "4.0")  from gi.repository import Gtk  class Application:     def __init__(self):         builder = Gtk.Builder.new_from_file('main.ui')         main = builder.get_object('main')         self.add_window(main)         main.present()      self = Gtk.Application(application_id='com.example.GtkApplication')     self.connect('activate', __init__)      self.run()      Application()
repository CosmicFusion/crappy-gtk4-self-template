import gi

gi.require_version("Gtk", "4.0")

from gi.repository import Gtk

class Application:
    def __init__(self):
        builder = Gtk.Builder.new_from_file('main.ui')
        main = builder.get_object('main')
        self.add_window(main)
        main.present()

    self = Gtk.Application(application_id='com.example.GtkApplication')
    self.connect('activate', __init__)

    self.run()
    
Application()

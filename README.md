Calendar
========

Could not find calendar widget in Kivy. This is my attempt which seems to work well on Windows and Android. 
Did not test on iOS. DISPLAY IT IN ZEN MODE.

from joecal import DateInput
from kivy.app import App
class TestApp(App):
	def build(self):
		di=DateInput('ButName','1/1/11')
		return di
TestApp().run()

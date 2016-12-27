vi /usr/lib/plexmediaserver/Resources/Plug-ins-b38628e/Framework.bundle/Contents/Resources/Versions/2/Python/Framework/components/data.py

change text to text.decode('utf8')


  class XML(SubComponent):

    def _construct_el(self, el, text, kwargs):
      if text:
      el.text = text.decode('utf8')Preferences

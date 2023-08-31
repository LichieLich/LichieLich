### Hi there <img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="24px" height="24px" alt="hi"> My name is Stas
Coding enthusiast from Russia. Currently working as a QA automation engineer and studying Ruby on Rails web development. Want to be expirienced enough to become open source contributor. Dreaming about creating some new useful tools for everyday job automation.
```ruby
class Me
  class << self
    attr_reader :name, :role, :language_spoken
  end

  @name = 'Stanislav Kolkov'
  @role = 'QA automation engineer'
  @language_spoken = ['ru', 'en']
end

class About < Me
  def code_available
    { ruby: 'medium', java: 'low' }
  end

  def known_technologies
    {
      web_back: ['Rails', 'Active Record', 'Devise', 'I18n'],
      ruby_common: ['Rspec', 'Minitest', 'Rubocop'],
      fronted: ['HTML', 'CSS', 'Bootstrap', 'Slim'],
      database: ['SQLite', 'PostgreSQL', 'Oracle DB'],
      autotests: ['Selenium', 'Cucumber', 'Capybara', 'Site Prism']
    }
  end

  def hobbies
    ['Coding', 'Guitar', 'Bass', 'Snowboarding', 'Videogames', 'Martial arts']
  end

  def say_hello
    puts "Hello! My name is #{Me.name} and I'm a #{Me.role}. What I can do:"
    pp code_available, known_technologies
    puts 'What I like to do:'
    pp hobbies
  end
end

me = About.new
me.say_hello
```
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=lichielich&layout=compact)

📊 **This week i spent my time on:**
<!--START_SECTION:waka-->

```txt
Ruby             2 hrs 36 mins   ██████████████████▒░░░░░░   72.76 %
Slim             53 mins         ██████▒░░░░░░░░░░░░░░░░░░   25.06 %
JSON             3 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.60 %
YAML             0 secs          ░░░░░░░░░░░░░░░░░░░░░░░░░   00.40 %
Objective-C      0 secs          ░░░░░░░░░░░░░░░░░░░░░░░░░   00.07 %
```

<!--END_SECTION:waka-->

![LichieLich's github stats](https://github-readme-stats.vercel.app/api?username=lichielich&count_private=true&show_icons=true&theme=onedark)

Reach me:

<img src="https://user-images.githubusercontent.com/72043094/183534048-902ae22c-0cf1-463b-9c0c-5906f20f41df.png" width="30" height="20" alt="e-mail"> lichie_lich@mail.ru

<img src="https://user-images.githubusercontent.com/72043094/183533973-b6dc2214-1439-4b78-8dae-5a7064e5cd0d.jpg" width="28" height="28" alt="e-mail"> @skolkov

Just a random programming joke:

![Jokes Card](https://readme-jokes.vercel.app/api)

<img src='https://random-memer.herokuapp.com/' title="Meme" alt="Please refresh the page if the meme doesn't show up.">

class imadevFS(self):
        self.username = 'imadevFS'
        self.name = 'Imanol Mugueta'
        self.web = 'En desarrollo'
        self.twitter = '@imadevFS'
        self.youtube = 'https://www.youtube.com/'
        self.linkedin = 'https://www.linkedin.com/'
        self.dev = 'https://dev.to/'
        self.source = {
            'born': ['Pamplona','Navarra','Spain'],
            'Where I live': ['Spain','Pamplona'],
        },
        self.studies = {
            'FPS': ['DAM','U-tad'],
            'FPS': ['Marketing','CI Maria Ana Sanz']
        },
        self.code = {
            'erp': ['odoo erp', 'sap r3'],
            'frontend': ['HTML', 'CSS', 'JavaScript', 'Boostrap','React','Redux'],
            'backend': ['Python', 'PHP', 'Flask', 'Django','Node.Js'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'MongoDB'],
            'devops': ['Docker', 'Nginx', 'AWS', 'Heroku','Docker-compose'],
            'tools': ['GIT', 'GitHub', 'Bitbucket'],
            'ides': ['Visual Studio Code', 'PyCharm'],
            'misc': ['Firebase', 'SCRUM', 'GNU/Linux', 'IOS']
        },
        self.projects = {
            'docker-odoo-16': [ https://github.com/docker-odoo-16 ][PYTHON],
        }
    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = imadevFS()


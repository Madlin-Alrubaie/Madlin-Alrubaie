class RafnixG:

    def __init__(self):
        self.username = 'rafnixg'
        self.name = 'Rafnix Guzmán'
        self.position = 'Python Software Developer'
        self.web = 'https://rafnixg.dev'
        self.links = 'https://links.rafnixg.dev'
        self.blog = 'https://blog.rafnixg.dev'
        self.cv = 'https://resume.rafnixg.dev'
        self.twitter = '@rafnixg'
        self.code = {
            'backend': ['Python', 'Odoo', 'Flask', 'Django', 'FastAPI', 'NodeJS', 'PHP'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'Mongo DB', 'Redis'],
            'devops': ['Docker', 'Linux', 'Jenkins', 'GitHub Actions', 'AWS', 'Proxmox'],
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS', 'Svelte', 'Boostrap'],
            'tools': ['GIT', 'GitHub', 'GitLab', 'Pandas', 'Jupyter notebook', 'SQLAlchemy', 'Celery', 'Nginx'],
            'misc': ['Firebase', 'TDD', 'SCRUM', 'SOLID', 'gRPC', 'ML', 'Tech Writer']
        }
        self.architecture = ['SPA', 'MVC', 'Serverless', 'microservices']

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = RafnixG()
    print(me)
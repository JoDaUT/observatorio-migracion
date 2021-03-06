# Observatorio de Migración

<br>

This project was created for the Community Service TCU-652 called "Migrantes como sujetos políticos" at Universidad de Costa Rica. The team was conformed by 1 History students, 1 Philology students and 2 Computer Science students.

## Target audience

Migrants living in Costa Rica.


## Requirements



### Users
The system must have two kind of users:
- The editor can manage posts (create, delete, update, read).
- The admin has the same permissions as an editor and has the ability to add or remove users.


### The blog


- A website where students and proffesors can post content focused on costarrican migration. 
- A post can contain images, videos, links just like any blog post. The dashboard must allow to manage these post, filter and order the posts.
- These post must have a system category for posts. The administrator can create, edit and remove categories. The editors just can use these categories, not modify them.
- The blog page has a search filter to find easier posts about an specific topic and the users have to be able to filter by categories.


### Telephone directory
A page that contains information about institutions and places related with migration in the country. The info must be shown in ascending order. Additionally, a search filter for the contacts.


### About section
It contains information about the webpage purpose.


## Tecnologies selection
The project required an original design and it has to be easy to use for the people. 

We choose Angular because the facility to reuse code in components, models and services. The code structure that generate automatically is easier than just with HTML, CSS and JS. Also, the observables that were helpful making the dinamic search filter and the category filter, that updates without reload the page.

Additional frontend tools: Boostrap, Angular Material.

For the admin dashboard we choose Strapi. It is a Open source Node.js Headless CMS. It makes very easy to manage the posts, filtered, ordered and allow the editors to have drafts before publising content.


## Solution implementation

We used a color palleted given by the Community Service Coordinator and we design the prototypes in AdobeXD. We started to code as soon as the design was approved.

- The solution includes: home, blog, about, and directory pages.
- Dark and light mode.
- Search and filter in blog page and directory page.
- Events section in home page.
- Category system.

### Frontend video

https://user-images.githubusercontent.com/47344349/149630846-8acdac87-ba04-4fab-9910-63f46f1e87e5.mp4



### CMS video
https://user-images.githubusercontent.com/47344349/149630001-e987c744-c969-43e7-9fa4-2d987c86a30b.mp4



## Run your own


### Version
You must have installed Angular 11.1.2 in your computer.


### Development server
First, `npm i` to install node dependencies.
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.


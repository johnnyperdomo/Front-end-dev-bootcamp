<template>
    <div id="app">
        <!-- navbar -->

        <!-- anything under the md will just show the hamburger menu; only expand on large-->
        <nav class="navbar navbar-expand-md bg-dark navbar-dark py-3 fixed-top">
            <div class="container">
                <a href="" class="navbar-brand">Frontend Bootcamp</a>

                <!-- button to toggle collapse on specific target -->
                <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navmenu">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <!-- collapse on smaller screens -->
                <div class="collapse navbar-collapse" id="navmenu">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a href="#learn" class="nav-link">What you'll learn</a>
                        </li>
                        <li class="nav-item">
                            <a href="#questions" class="nav-link">Questions</a>
                        </li>
                        <li class="nav-item">
                            <a href="#instructors" class="nav-link">Instructors</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <!-- showcase -->

        <!-- starting at the 'small' breakpoint, align the text to the start; breakpoints cascade up -->
        <section class="bg-dark text-light p-5 text-center text-sm-start">
            <div class="container">
                <!-- flexbox; turns it into a row; sm only turns it into a row when it reaches the small screen size -->
                <div class="d-sm-flex align-items-center justify-content-between">
                    <!-- flexitems -->

                    <div>
                        <h1>Become a <span class="text-warning">Web Developer</span></h1>
                        <p class="lead my-4">
                            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eaque quod
                            incidunt reiciendis tempora iusto voluptates aspernatur vero consectetur
                            dolores suscipit, minus perspiciatis, iste molestiae aliquam accusamus
                            earum officia reprehenderit? Soluta?
                        </p>
                        <button
                            class="btn btn-primary btn-lg"
                            data-bs-toggle="modal"
                            data-bs-target="#enroll"
                        >
                            Start The Enrollment
                        </button>
                    </div>

                    <img
                        src="./assets/programming.svg"
                        alt=""
                        class="img-fluid w-50 d-none d-sm-block"
                    />
                </div>
            </div>
        </section>

        <!-- newsletter -->

        <section class="bg-primary text-light p-5">
            <div class="container">
                <div class="d-md-flex justify-content-around align-items-center">
                    <h3 class="mb-3 mb-md-0 text-center">Sign up for our newsletter</h3>

                    <div class="input-group news-input">
                        <input
                            type="text"
                            class="form-control"
                            placeholder="Enter Email"
                            aria-label="Enter Email"
                        />
                        <button class="btn btn-dark btn-lg">Button</button>
                    </div>
                </div>
            </div>
        </section>

        <!-- boxes -->
        <section class="p-5">
            <div class="container">
                <div class="row text-center g-4">
                    <div class="col-md">
                        <div class="card bg-dark text-white">
                            <div class="card-body text-center">
                                <div class="h1 mb-3">
                                    <i class="bi bi-laptop"></i>
                                </div>
                                <h3 class="card-title mb-3">Virtual</h3>
                                <p class="card-text">
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit
                                    inventore quae quidem nam at nulla?
                                </p>

                                <a href="#" class="btn btn-primary">Read More</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md">
                        <div class="card bg-secondary text-white">
                            <div class="card-body text-center">
                                <div class="h1 mb-3">
                                    <i class="bi bi-person-square"></i>
                                </div>
                                <h3 class="card-title mb-3">Hybrid</h3>
                                <p class="card-text">
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit
                                    inventore quae quidem nam at nulla?
                                </p>

                                <a href="#" class="btn btn-dark">Read More</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md">
                        <div class="card bg-dark text-white">
                            <div class="card-body text-center">
                                <div class="h1 mb-3">
                                    <i class="bi bi-people"></i>
                                </div>
                                <h3 class="card-title mb-3">In Person</h3>
                                <p class="card-text">
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit
                                    inventore quae quidem nam at nulla?
                                </p>

                                <a href="#" class="btn btn-primary">Read More</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Learn sections -->

        <section id="learn" class="p-5">
            <div class="container">
                <div class="row align-items-center justify-content-between">
                    <div class="col-md">
                        <img src="./assets/fundamentals.svg" alt="" class="img-fluid" />
                    </div>

                    <div class="col-md p-5">
                        <h2>Learn the Fundamentals</h2>
                        <p class="lead">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, atque
                            sapiente fugit praesentium ut placeat eos ullam quasi veniam
                            perspiciatis tempore, mollitia saepe delectus maxime vel ipsum suscipit
                            assumenda dolorum!
                        </p>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex culpa nobis
                            iste quas sit facere omnis fugiat veniam fuga maiores provident
                            possimus, nisi eum, consequatur veritatis vero distinctio commodi.
                            Molestias?
                        </p>

                        <a href="" class="btn btn-light mt-3">
                            <i class="bt bi-chevron-right"> Read More </i>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <section class="p-5 bg-dark text-light">
            <div class="container">
                <div class="row align-items-center justify-content-between">
                    <div class="col-md p-5">
                        <h2>Learn React</h2>
                        <p class="lead">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, atque
                            sapiente fugit praesentium ut placeat eos ullam quasi veniam
                            perspiciatis tempore, mollitia saepe delectus maxime vel ipsum suscipit
                            assumenda dolorum!
                        </p>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex culpa nobis
                            iste quas sit facere omnis fugiat veniam fuga maiores provident
                            possimus, nisi eum, consequatur veritatis vero distinctio commodi.
                            Molestias?
                        </p>

                        <a href="" class="btn btn-light mt-3">
                            <i class="bt bi-chevron-right"> Read More </i>
                        </a>
                    </div>
                    <div class="col-md">
                        <img src="./assets/react.svg" alt="" class="img-fluid" />
                    </div>
                </div>
            </div>
        </section>

        <!-- Quesition accordion -->

        <section id="questions" class="p-5">
            <div class="container">
                <h2 class="text-center mb-4">Frequently asked questions</h2>
                <div class="accordion accordion-flush" id="questions">
                    <!-- item 1 -->
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button
                                class="accordion-button collapsed"
                                type="button"
                                data-bs-toggle="collapse"
                                data-bs-target="#question-one"
                            >
                                Where are you located?
                            </button>
                        </h2>
                        <div
                            id="question-one"
                            class="accordion-collapse collapse"
                            data-bs-parent="#questions"
                        >
                            <div class="accordion-body">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla at,
                                amet delectus aliquam odit dolore. Soluta tempora expedita provident
                                velit aliquid minima, recusandae inventore assumenda, eos et natus
                                harum rem perferendis iusto. Tempora aliquid minus vero quo
                                voluptatibus obcaecati laudantium est ipsum corporis sint iste hic,
                                corrupti ea fugiat quod.
                            </div>
                        </div>
                    </div>

                    <!-- item 2 -->

                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button
                                class="accordion-button collapsed"
                                type="button"
                                data-bs-toggle="collapse"
                                data-bs-target="#question-two"
                            >
                                How much is the cost to attend?
                            </button>
                        </h2>
                        <div
                            id="question-two"
                            class="accordion-collapse collapse"
                            data-bs-parent="#questions"
                        >
                            <div class="accordion-body">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla at,
                                amet delectus aliquam odit dolore. Soluta tempora expedita provident
                                velit aliquid minima, recusandae inventore assumenda, eos et natus
                                harum rem perferendis iusto. Tempora aliquid minus vero quo
                                voluptatibus obcaecati laudantium est ipsum corporis sint iste hic,
                                corrupti ea fugiat quod.
                            </div>
                        </div>
                    </div>

                    <!-- item 3 -->

                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button
                                class="accordion-button collapsed"
                                type="button"
                                data-bs-toggle="collapse"
                                data-bs-target="#question-three"
                            >
                                What do I need to know?
                            </button>
                        </h2>
                        <div
                            id="question-three"
                            class="accordion-collapse collapse"
                            data-bs-parent="#questions"
                        >
                            <div class="accordion-body">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla at,
                                amet delectus aliquam odit dolore. Soluta tempora expedita provident
                                velit aliquid minima, recusandae inventore assumenda, eos et natus
                                harum rem perferendis iusto. Tempora aliquid minus vero quo
                                voluptatibus obcaecati laudantium est ipsum corporis sint iste hic,
                                corrupti ea fugiat quod.
                            </div>
                        </div>
                    </div>

                    <!-- Item 4 -->
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button
                                class="accordion-button collapsed"
                                type="button"
                                data-bs-toggle="collapse"
                                data-bs-target="#question-four"
                            >
                                How do i sign up?
                            </button>
                        </h2>
                        <div
                            id="question-four"
                            class="accordion-collapse collapse"
                            data-bs-parent="#questions"
                        >
                            <div class="accordion-body">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla at,
                                amet delectus aliquam odit dolore. Soluta tempora expedita provident
                                velit aliquid minima, recusandae inventore assumenda, eos et natus
                                harum rem perferendis iusto. Tempora aliquid minus vero quo
                                voluptatibus obcaecati laudantium est ipsum corporis sint iste hic,
                                corrupti ea fugiat quod.
                            </div>
                        </div>
                    </div>

                    <!-- Item 5 -->
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button
                                class="accordion-button collapsed"
                                type="button"
                                data-bs-toggle="collapse"
                                data-bs-target="#question-five"
                            >
                                Do you help me find a job?
                            </button>
                        </h2>
                        <div
                            id="question-five"
                            class="accordion-collapse collapse"
                            data-bs-parent="#questions"
                        >
                            <div class="accordion-body">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla at,
                                amet delectus aliquam odit dolore. Soluta tempora expedita provident
                                velit aliquid minima, recusandae inventore assumenda, eos et natus
                                harum rem perferendis iusto. Tempora aliquid minus vero quo
                                voluptatibus obcaecati laudantium est ipsum corporis sint iste hic,
                                corrupti ea fugiat quod.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- instructors -->

        <section id="isntructors" class="p-5 bg-primary">
            <div class="container">
                <h2 class="text-center text-white">Our instructors</h2>
                <p class="lead text-white text-center mb-5">
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut, vel, illum
                    consequatur laboriosam odit exercitationem explicabo error mollitia debitis
                    perspiciatis saepe sapiente magni fuga facere labore iusto commodi. Aut, quod?
                </p>
                <div class="row g-4">
                    <div class="col-md-6 col-lg-3">
                        <div class="card bg-light">
                            <div class="card-body text-center">
                                <img
                                    src="https://randomuser.me/api/portraits/men/11.jpg"
                                    class="rounded-circle mb-3"
                                    alt=""
                                    srcset=""
                                />
                                <h3 class="card-title mb-3">John Doe</h3>
                                <p class="card-text">
                                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quidem
                                    doloremque laboriosam a accusantium magni, suscipit corrupti
                                    quam illo aut deserunt fuga ut mollitia odio tenetur, recusandae
                                    consectetur architecto iste sapiente.
                                </p>
                                <a href="#"> <i class="bi bi-twitter text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-facebook text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-linkedin text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-instagram text-dark mx-1"> </i></a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3">
                        <div class="card bg-light">
                            <div class="card-body text-center">
                                <img
                                    src="https://randomuser.me/api/portraits/women/11.jpg"
                                    class="rounded-circle mb-3"
                                    alt=""
                                    srcset=""
                                />
                                <h3 class="card-title mb-3">Jane Doe</h3>
                                <p class="card-text">
                                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quidem
                                    doloremque laboriosam a accusantium magni, suscipit corrupti
                                    quam illo aut deserunt fuga ut mollitia odio tenetur, recusandae
                                    consectetur architecto iste sapiente.
                                </p>
                                <a href="#"> <i class="bi bi-twitter text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-facebook text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-linkedin text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-instagram text-dark mx-1"> </i></a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3">
                        <div class="card bg-light">
                            <div class="card-body text-center">
                                <img
                                    src="https://randomuser.me/api/portraits/men/12.jpg"
                                    class="rounded-circle mb-3"
                                    alt=""
                                    srcset=""
                                />
                                <h3 class="card-title mb-3">Steve Smith</h3>
                                <p class="card-text">
                                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quidem
                                    doloremque laboriosam a accusantium magni, suscipit corrupti
                                    quam illo aut deserunt fuga ut mollitia odio tenetur, recusandae
                                    consectetur architecto iste sapiente.
                                </p>
                                <a href="#"> <i class="bi bi-twitter text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-facebook text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-linkedin text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-instagram text-dark mx-1"> </i></a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3">
                        <div class="card bg-light">
                            <div class="card-body text-center">
                                <img
                                    src="https://randomuser.me/api/portraits/women/12.jpg"
                                    class="rounded-circle mb-3"
                                    alt=""
                                    srcset=""
                                />
                                <h3 class="card-title mb-3">Sarah Smith</h3>
                                <p class="card-text">
                                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quidem
                                    doloremque laboriosam a accusantium magni, suscipit corrupti
                                    quam illo aut deserunt fuga ut mollitia odio tenetur, recusandae
                                    consectetur architecto iste sapiente.
                                </p>
                                <a href="#"> <i class="bi bi-twitter text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-facebook text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-linkedin text-dark mx-1"> </i></a>
                                <a href="#"> <i class="bi bi-instagram text-dark mx-1"> </i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- contact  -->
        <section class="p-5">
            <div class="container">
                <h2 class="text-center mb-4">Contact Info</h2>

                <ul class="list-group list-group-flush lead text-center">
                    <li class="list-group-item">
                        <span class="fw-bold">Main Location:</span> 50 Main St Boston MA
                    </li>
                    <li class="list-group-item">
                        <span class="fw-bold">Enrollment Phone:</span> 123-456-7866
                    </li>
                    <li class="list-group-item">
                        <span class="fw-bold">Student Phone:</span> 123-456-7866
                    </li>
                    <li class="list-group-item">
                        <span class="fw-bold">Enrollment Email:</span> enroll@example.com
                    </li>
                    <li class="list-group-item">
                        <span class="fw-bold">Student Email:</span> student@example.com
                    </li>
                </ul>
            </div>
        </section>

        <!-- Footer -->
        <footer class="p-5 bg-dark text-white text-center position-relative">
            <div class="container">
                <p class="lead">Copyright &copy; 2021 Frontend Bootcamp</p>
                <a href="" class="position-absolute bottom-0 end-0 p-5">
                    <i class="bi bi-arrow-up-circle h1"></i>
                </a>
            </div>
        </footer>

        <!-- Modal -->
        <div
            class="modal fade"
            id="enroll"
            tabindex="-1"
            aria-labelledby="enrollLabel"
            aria-hidden="true"
        >
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                        <button
                            type="button"
                            class="btn-close"
                            data-bs-dismiss="modal"
                            aria-label="Close"
                        ></button>
                    </div>
                    <div class="modal-body">
                        <p class="lead">Fill out this form and we will get back to you</p>
                        <form>
                            <div class="mb-3">
                                <label for="first-name" class="col-form-label">First Name:</label>
                                <input type="text" class="form-control" id="first-name" />
                            </div>

                            <div class="mb-3">
                                <label for="email" class="col-form-label">Email:</label>
                                <input type="text" class="form-control" id="email" />
                            </div>

                            <div class="mb-3">
                                <label for="phone" class="col-form-label">Phone:</label>
                                <input type="text" class="form-control" id="phone" />
                            </div>
                        </form>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">
                            Close
                        </button>
                        <button type="button" class="btn btn-primary">Submit</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "App",
};
</script>

<style>
/* larger than the mobile size; make input larger */
@media (min-width: 768px) {
    .news-input {
        width: 50%;
    }
}

/* adds a ghost element of 60px */
body::before {
    display: block;
    content: "";
    height: 60px;
}
</style>
